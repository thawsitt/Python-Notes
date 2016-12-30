#Python built-in data structures
1. [List](#list)
2. [Dictionary](#dictionary)

## List
Lists are **mutable** sequence type in Python. [(PyDoc)][1]

### Initializing lists
* Use square brackets to initialize lists.
```python
empty_list = []
scores = [81, 86, 97, 99, 97, 99]
```

* You can also use **list()** function to create lists from other types.
```python
empty_list = list()
str_list = list('abc')    # ['a', 'b', 'c']
```
- - -

### Looping lists
* Basic Usage
```python
for item in list:
    print(item)
```
* Additional: **sorted()** function
```python
for item in sorted(list):
    print(item)
```

* **enumerate()**: to get both **index** and **value** at the same time.
```python
>>> for i, v in enumerate(['tic', 'tac', 'toe']):
...     print(i, v)
...
0 tic
1 tac
2 toe
```

## Dictionary
Dictionary is an **unordered** set of key-value pairs. [(PyDoc)][2]

### Initializing dicts
* Use curly braces and **'key' : value** format.
```python
school_years = {'freshman' : 1, 'sophomore' : 2, 'junior' : 3, 'senior' : 4}
```

* You can also use **dict()** function.
```python
empty_dict = dict()
dict_from_sequences = {('john', 29), ('mike', 25), ('justin', 21)}
```

### Accessing dicts
* Use the square bracket [] and keyword to access the value.
```python
scores = {'Stanford' : 10, 'Cal' : 8, 'USC' : 9}
my_score = scores['Stanford']
```

### Looping dicts
* **items()** method is your friend for looping dictionaries.
```python
knights = {'gallahad': 'the pure', 'robin': 'the brave'}
>>> for k, v in knights.items():
...     print(k, v)
...
gallahad the pure
robin the brave
```


[1]: https://docs.python.org/3.1/tutorial/datastructures.html#more-on-lists
[2]: https://docs.python.org/3.1/tutorial/datastructures.html#dictionaries
