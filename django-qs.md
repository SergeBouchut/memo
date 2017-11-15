Django QuerySet
===============

Bitwise operations
------------------ 

```
class Notes(models.Model):
    FLAG_TODO = 0b0001
    FLAG_WORK = 0b0010
```

Get all notes TODO:
```
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO))
```

Get all notes except TODO:
```
Notes.objects.filter(flags=F('flags').bitand(~Notes.FLAG_TODO))
```

Get all notes TODO for WORK:
```
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO).bitor(Notes.FLAG_WORK))
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO | Notes.FLAG_WORK))
```

Get all notes TODO except those for WORK:
```
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO).bitand(~Notes.FLAG_WORK))
```

Get all notes except those TODO for WORK:
```
###Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO).bitand(~Notes.FLAG_WORK))
```

Get all notes except those TODO or those for WORK:
```
Notes.objects.filter(flags=F('flags').bitand(~Notes.FLAG_TODO).bitand(~Notes.FLAG_WORK))
Notes.objects.filter(flags=F('flags').bitand(~Notes.FLAG_TODO & ~Notes.FLAG_WORK))
Notes.objects.filter(flags=F('flags').bitand(~(Notes.FLAG_TODO | Notes.FLAG_WORK)))


```
