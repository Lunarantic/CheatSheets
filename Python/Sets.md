# Set

```python
>>> set([1, 2, 2, 3])
set([1, 2, 3])
>>> a = set('lunarantic')
set(['a', 'c', 'i', 'l', 'n', 'r', 'u', 't'])
>>> b = set('python')
set(['h', 'o', 'n', 'p', 't', 'y'])
>>> type(a)
<type 'str'>
```

### Operations
Union
```python
>>> a.union(b)
>>> a | b
set(['a', 'c', 'i', 'h', 'l', 'o', 'n', 'p', 'r', 'u', 't', 'y'])
```
Intersection
```python
>>> a.intersection(b)
>>> a & b
set(['t', 'n'])
```
Difference
```python
>>> a.difference(b)
>>> a - b
set(['a', 'c', 'i', 'l', 'r', 'u'])
```
Symmetric Difference
```python
>>> a.symmetric_difference(b)
>>> a ^ b
set(['a', 'c', 'i', 'h', 'l', 'o', 'p', 'r', 'u', 'y'])
```

### Update Operations
By Union
```python
>>> a.update(b)
>>> a |= b
set(['a', 'c', 'i', 'h', 'l', 'o', 'n', 'p', 'r', 'u', 't', 'y'])
```
By Intersection
```python
>>> a.intersection_update(b)
>>> a &= b
set(['t', 'n'])
```
By Difference
```python
>>> a.difference_update(b)
>>> a += b
set(['a', 'c', 'i', 'l', 'r', 'u'])
```
By Symmetric Difference
```python
>>> a.symmetric_difference_update(b)
>>> a -= b
set(['a', 'c', 'i', 'h', 'l', 'o', 'p', 'r', 'u', 'y'])
```
