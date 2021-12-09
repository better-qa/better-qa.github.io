# Common Data Type
## Int
1. **int** data type can represents all integers, positive or negative.
    - e.g. -2589, -123, -1, 0, 1, 15, 256, 4567 are int in Python


2. **[Min / Max value in Python 3](https://docs.python.org/3/whatsnew/3.0.html#integers)**

    - According to Python 3 documentation, **sys.maxsize** can be used as an integer larger than any practical list or string index

> [sys.maxsize](https://docs.python.org/3/library/sys.html#sys.maxsize)
> 
> An integer giving the maximum value a variable of type Py_ssize_t can take. It’s usually 2**31 - 1 on a 32-bit platform and 2**63 - 1 on a 64-bit platform.


## Float
1. **float** data type can represents all floating point numbers, positive or negative.
    - e.g. -3.1, -.5, .2, 8., 2.0, 10.2, -23.28382983, 3.14 are float in Python
    - 2.0, .5, 8. are considered as float because of the presence of decimal point (.)


## String
1. **string** data type can represents sequence of characters. They start and end with ", ', """ or '''.
    - e.g. "hello", '3.14', """False""", '''true'''


## Bool
1. **bool** data type can represents one of 2 values: True or False



# Referrence
Above are some data type we usually use, for more information please visit [Python3 documentation](https://docs.python.org/3/library/stdtypes.html)
  - Numeric Types — int, float, complex
  - Iterator Types
    - Python supports a concept of iteration over containers. This is implemented using two distinct methods; these are used to allow user-defined classes to support iteration. Sequences, described below in more detail, always support the iteration methods.
  - Generator Types
    - Python’s generators provide a convenient way to implement the iterator protocol. If a container object’s __iter__() method is implemented as a generator, it will automatically return an iterator object (technically, a generator object) supplying the __iter__() and __next__() methods. More information about generators can be found in the documentation for the yield expression.
  - Sequence Types — list, tuple, range
    - There are three basic sequence types: lists, tuples, and range objects. Additional sequence types tailored for processing of binary data and text strings are described in dedicated sections.
  - Text Sequence Type
    - Textual data in Python is handled with str objects, or strings. Strings are immutable sequences of Unicode code points
  - Binary Sequence Types — bytes, bytearray, memoryview
  - Set Types — set, frozenset
    - A set object is an unordered collection of distinct hashable objects. Common uses include membership testing, removing duplicates from a sequence, and computing mathematical operations such as intersection, union, difference, and symmetric difference. (For other containers see the built-in dict, list, and tuple classes, and the collections module.)
  - Mapping Types — dict
    - A mapping object maps hashable values to arbitrary objects. Mappings are mutable objects. There is currently only one standard mapping type, the dictionary. (For other containers see the built-in list, set, and tuple classes, and the collections module.)
  - Context Manager Types
    - Python’s with statement supports the concept of a runtime context defined by a context manager. This is implemented using a pair of methods that allow user-defined classes to define a runtime context that is entered before the statement body is executed and exited when the statement ends
  - Type Annotation Types — Generic Alias, Union
    - The core built-in types for type annotations are Generic Alias and Union.









