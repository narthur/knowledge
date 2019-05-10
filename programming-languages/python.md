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

Get list of dictionary keys sorted by their values \([source](https://www.pythoncentral.io/how-to-sort-python-dictionaries-by-key-or-value/)\):

```python
numbers = {'first': 1, 'second': 2, 'third': 3, 'Fourth': 4}
# Use the __getitem__ method as the key function
sorted(numbers, key=numbers.__getitem__)
# In order of sorted values: [1, 2, 3, 4]
['first', 'second', 'third', 'Fourth']
```

## Links

[Python File I/O](https://www.programiz.com/python-programming/file-operation) \#article - "In this article, you'll learn about Python file operations. More specifically, opening a file, reading from it, writing into it, closing it and various file methods you should be aware of."

### Books

\_\_[_Elegant SciPy_](https://github.com/elegant-scipy/elegant-scipy) by Juan Nunez-Iglesias, Stefan van der Walt & Harriet Dashnow

\_\_[_Flask Web Development_](https://doc.lagout.org/programmation/python/Flask%20Web%20Development_%20Developing%20Web%20Applications%20with%20Python%20%5BGrinberg%202014-05-18%5D.pdf) __by Miguel Grinberg

_Fluent Python_ by Luciano Ramalho

\_\_[_The Hitchhiker's Guide to Python_](https://docs.python-guide.org/) by Kenneth Reitz & Tanya Schlusser

_Introducing Python_ by Bill Lubanovic

\_\_[_Natural Language Processing with Python_](https://www.amazon.com/Natural-Language-Processing-Python-Analyzing/dp/0596516495) __by Steven Bird, Ewan Klein, Edward Loper - "This book offers a highly accessible introduction to natural language processing, the field that supports a variety of language technologies, from predictive text and email filtering to automatic summarization and translation. With it, you'll learn how to write Python programs that work with large collections of unstructured text. You'll access richly annotated datasets using a comprehensive range of linguistic data structures, and you'll understand the main algorithms for analyzing the content and structure of written communication."

\_\_[_Python Data Science Handbook_](https://jakevdp.github.io/PythonDataScienceHandbook/) by Jake VanderPlas

\_\_[_Test-Driven Development with Python_](https://doc.lagout.org/programmation/python/Test-Driven%20Development%20with%20Python_%20Obey%20the%20Testing%20Goat_%20Using%20Django%2c%20Selenium%2c%20and%20JavaScript%20%5bPercival%202014-06-29%5d.pdf) by Harry J.W. Percival

\_\_[_Think Bayes_](https://greenteapress.com/wp/think-bayes/) by Allen B. Downey

\_\_[_Think Python, 2nd Edition_](https://greenteapress.com/wp/think-python-2e/) by Allen B. Downey

\_\_[_Thoughtful Machine Learning with Python_](https://www.oreilly.com/library/view/thoughtful-machine-learning/9781491924129/) __by Matthew Kirk

_Twisted Network Programming Essentials_ by Jessica McKellar & Abe Fettig

_Web Scraping with Python_ by Ryan Mitchell

### matplotlib

[Matplotlib trendline](http://widu.tumblr.com/post/43624347354/matplotlib-trendline) \#article - "Drawing a trendline of a scatter plot in matplotlib is very easy thanks to numpy’s polyfit function."

