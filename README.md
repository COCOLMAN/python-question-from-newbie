# ???????



```
일단 listup만 진행. 추후 답변추가 및 리팩토링

```


1. float형에서 특정 소수점 이하는 무시되네요? 왜 그런가요?

```


```


2. packing될때 tuple, list?

```

>>> a = 1, 2
>>> a
(1, 2)
>>> type(a)
<class 'tuple'>
>>> a, *b = 1, 2, 3, 4
>>> a
1
>>> b
[2, 3, 4]
>>> type(b)
<class 'list'>

```


3.
