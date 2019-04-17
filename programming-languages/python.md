# Python

## Snippets

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

Convert between time formats \([source](https://stackoverflow.com/questions/9637838/convert-string-date-to-timestamp-in-python/9637908#9637908), [source](https://www.programiz.com/python-programming/datetime/timestamp-datetime)\):

```python
import datetime
import time

# timestamp to datetime
timestamp = 1545730073
dt_object = datetime.datetime.fromtimestamp(timestamp)

# datetime to timestamp
now = datetime.datetime.now()
timestamp = datetime.datetime.timestamp(now)

# date string to timestamp
s = "01/12/2011"
timestamp = time.mktime(datetime.datetime.strptime(s, "%d/%m/%Y").timetuple())
```

## Links

[Python File I/O](https://www.programiz.com/python-programming/file-operation) \#article - "In this article, you'll learn about Python file operations. More specifically, opening a file, reading from it, writing into it, closing it and various file methods you should be aware of."

### matplotlib

[Matplotlib trendline](http://widu.tumblr.com/post/43624347354/matplotlib-trendline) \#article - "Drawing a trendline of a scatter plot in matplotlib is very easy thanks to numpy’s polyfit function."

