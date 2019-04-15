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

[Convert between Unix timestamps and datetime objects](https://www.programiz.com/python-programming/datetime/timestamp-datetime):

```python
from datetime import datetime

# timestamp to datetime
timestamp = 1545730073
dt_object = datetime.fromtimestamp(timestamp)

# datetime to timestamp
now = datetime.now()
timestamp = datetime.timestamp(now)
```

[Convert date string to timestamp](https://stackoverflow.com/a/9637908/937377) \([formatting directives](https://docs.python.org/3/library/datetime.html#strftime-strptime-behavior)\):

```python
>>> import time
>>> import datetime
>>> s = "01/12/2011"
>>> time.mktime(datetime.datetime.strptime(s, "%d/%m/%Y").timetuple())
1322697600.0
```

## matplotlib

[Matplotlib trendline](http://widu.tumblr.com/post/43624347354/matplotlib-trendline) \#article - "Drawing a trendline of a scatter plot in matplotlib is very easy thanks to numpy’s polyfit function."

