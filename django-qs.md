Django QuerySet
===============

Bitwise operations
------------------

```
Model.objects.filter(flags=F('flags').bitor(Model.FLAG_1))
```
