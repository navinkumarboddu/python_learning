### dir() and help() function

```
tiger = "i am a tiger"

# Using dir() function
print(dir(tiger))

# Using help() function
help(tiger.upper)
```

Explanation

* Using dir() Function:
  <br />
\
  dir(tiger):
            The dir() function attempts to return a list of valid attributes and methods for the object.
            Here, dir(tiger) returns a list of all the attributes and methods associated with the string object tiger.
  <br />
\
  ```
  Output:
      ['__add__', '__class__', '__contains__', '__delattr__', '__dir__', '__doc__', '__eq__', '__format__', '__ge__', '__getattribute__', '__getitem__', '__getnewargs__', '__gt__', '__hash__', '__init__', '__init_subclass__', '__iter__', '__le__', '__len__', '__lt__', '__mod__', '__mul__', '__ne__', '__new__', '__reduce__', '__reduce_ex__', '__repr__', '__rmod__', '__rmul__', '__setattr__', '__sizeof__', '__str__', '__subclasshook__', 'capitalize', 'casefold', 'center', 'count', 'encode', 'endswith', 'expandtabs', 'find', 'format', 'format_map', 'index', 'isalnum', 'isalpha', 'isascii', 'isdecimal', 'isdigit', 'isidentifier', 'islower', 'isnumeric', 'isprintable', 'isspace', 'istitle', 'isupper', 'join', 'ljust', 'lower', 'lstrip', 'maketrans', 'partition', 'replace', 'rfind', 'rindex', 'rjust', 'rpartition', 'rsplit', 'rstrip', 'split', 'splitlines', 'startswith', 'strip', 'swapcase', 'title', 'translate', 'upper', 'zfill']
  ```
    <br />

* Using help() Function:
  <br />
  \
    help(tiger.upper):
        The help() function is used to display the documentation string for the object passed to it.
        Here, help(tiger.upper) provides detailed information about the upper method of the string object tiger.
  ```
  Output:
  Help on built-in function upper:
    upper() method of builtins.str instance
    Return a copy of the string converted to uppercase.
  ```