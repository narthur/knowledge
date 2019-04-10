# Python

[Generators](https://wiki.python.org/moin/Generators) allow you to [define lazy-loaded infinite sequences](https://medium.com/@dawranliou/lazy-codes-infinite-sequences-in-python-and-clojure-80bba720b3a3):

```python
def number_generator():
    i = 0
    while True:
        yield i
        i += 1
numbers = number_generator()
next(numbers)  # 0
next(numbers)  # 1
next(numbers)  # 2
next(numbers)  # 3
#...
```

[Find first item in iterable that satisfies a criterion](https://stackoverflow.com/a/9868665/937377):

```python
first = next(obj for obj in objs if obj.val==5)
```

