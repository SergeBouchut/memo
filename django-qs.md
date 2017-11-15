Django QuerySet
===============

Bitwise operations
------------------

Object with flag 1
```
Model.objects.filter(flags=F('flags').bitor(Model.FLAG_1))
```

Object without flag 1
```
Model.objects.filter(flags=F('flags').bitand(~Model.FLAG_1))
```
