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

Check of datetime object is localized \([source](https://stackoverflow.com/a/27596917/937377)\):

```python
d.tzinfo is not None and d.tzinfo.utcoffset(d) is not None
```

## Links

[How to use Python's unittest.mock.patch](https://www.youtube.com/watch?v=WFRljVPHrkE) \#video - "How to use \(and where to apply\) Python's unittest.mock.patch in your test suites. In this video I show where to patch, and three ways of applying mock.patch: as a decorator, as a context manager, and inline using mock.patch.start\(\) and mock.patch.stop\(\)."

[Is Python pass-by-reference or pass-by-value?](https://robertheaton.com/2014/02/09/pythons-pass-by-object-reference-as-explained-by-philip-k-dick/) \#article - " 'Object references are passed by value.' When I first read this smug and overly-pithy definition, I wanted to punch something."

[PyCharm](https://www.jetbrains.com/pycharm/?fromMenu) \#software - IDE. The community edition is free to use, [even at work](https://blog.jetbrains.com/pycharm/2017/09/pycharm-community-edition-and-professional-edition-explained-licenses-and-more/).

[Python File I/O](https://www.programiz.com/python-programming/file-operation) \#article - "In this article, you'll learn about Python file operations. More specifically, opening a file, reading from it, writing into it, closing it and various file methods you should be aware of."

[Python's `strftime` directives](http://strftime.org/) - "I need to use Python’s `strftime` rarely enough that I can’t remember it off the top of my head and never bookmark it but often enough to be annoyed with having to Google “python strftime” and then find the table above in the Python documentation. So I decided to put this reference page up."

[SnakeViz](https://jiffyclub.github.io/snakeviz/) \#software - "SnakeViz is a browser based graphical viewer for the output of Python’s [cProfile](https://docs.python.org/3/library/profile.html#module-cProfile) module and an alternative to using the standard library [pstats module](https://docs.python.org/3/library/profile.html#module-pstats). It was originally inspired by [RunSnakeRun](http://www.vrplumber.com/programming/runsnakerun/). SnakeViz works on Python 2.7 and Python 3. SnakeViz itself is still likely to work on Python 2.6, but official support has been dropped now that [Tornado](http://www.tornadoweb.org/) no longer supports Python 2.6."

[Traps for the Unwary in Python’s Import System](http://python-notes.curiousefficiency.org/en/latest/python_concepts/import_traps.html) \#article - "Python’s import system is powerful, but also quite complicated. Until the release of Python 3.3, there was no comprehensive explanation of the expected import semantics, and even following the release of 3.3, the details of how `sys.path` is initialised are still somewhat challenging to figure out."

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

### pytz

[List of tz database time zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) \#article - Wikipedia. "This is a list of time zones from release 2017c of the [tz database](https://en.wikipedia.org/wiki/Tz_database)."

[pytz on pypi](https://pypi.org/project/pytz/) - "pytz brings the Olson tz database into Python. This library allows accurate and cross platform timezone calculations using Python 2.4 or higher. It also solves the issue of ambiguous times at the end of daylight saving time, which you can read more about in the Python Library Reference \(`datetime.tzinfo`\)."

[pytz - World Timezone Definitions for Python](https://pythonhosted.org/pytz/) \#article - Docs. "pytz brings the Olson tz database into Python. This library allows accurate and cross platform timezone calculations using Python 2.4 or higher. It also solves the issue of ambiguous times at the end of daylight saving time, which you can read more about in the Python Library Reference \(datetime.tzinfo\)."

[Time Zone Database](http://www.iana.org/time-zones) - IANA. "The Time Zone Database \(often called tz or zoneinfo\) contains code and data that represent the history of local time for many representative locations around the globe. It is updated periodically to reflect changes made by political bodies to time zone boundaries, UTC offsets, and daylight-saving rules. Its management procedure is documented in [BCP 175: Procedures for Maintaining the Time Zone Database](http://www.iana.org/go/rfc6557)."

[tz database](https://en.wikipedia.org/wiki/Tz_database) \#article - Wikipedia. "The **tz database** is a collaborative compilation of information about the world's [time zones](https://en.wikipedia.org/wiki/Time_zone), primarily intended for use with computer programs and operating systems.[\[2\]](https://en.wikipedia.org/wiki/Tz_database#cite_note-2) Paul Eggert is its current editor and maintainer,[\[3\]](https://en.wikipedia.org/wiki/Tz_database#cite_note-3) with the organizational backing of [ICANN](https://en.wikipedia.org/wiki/ICANN).[\[4\]](https://en.wikipedia.org/wiki/Tz_database#cite_note-:0-4) The tz database is also known as **tzdata**, the **zoneinfo database** or **IANA time zone database**, and occasionally as the **Olson database**, referring to the founding contributor, Arthur David Olson.[\[5\]](https://en.wikipedia.org/wiki/Tz_database#cite_note-5)"

