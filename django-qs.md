Django QuerySet
===============

Bitwise operations
------------------ 

```
class Notes(models.Model):
    FLAG_TODO = 0b0001
    FLAG_WORK = 0b0010
```

Notes TODO
```
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO))
```

Object with flag 1 or flag 2
```
Notes.objects.filter(flags=F('flags').bitor(Notes.FLAG_TODO | Notes.FLAG_2))
```

Object without flag 1
```
Notes.objects.filter(flags=F('flags').bitand(~Notes.FLAG_TODO))
```

Object without flag 1 nor flag 2
```
Notes.objects.filter(flags=F('flags').bitand(~(Notes.FLAG_TODO | Notes.FLAG_2)))
```
