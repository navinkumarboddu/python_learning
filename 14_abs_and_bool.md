### 1. # Using abs() Function

```
abs(-43)
43
abs(2)
2
```

# Using bool() Function
```
bool(0)        
False
bool(1)        
True
bool(45)       
True
bool("asd")    
True
bool(None)     
False
```

Explanation
* Using abs() Function:
    abs(-43):
        The abs() function returns the absolute value of a number.
        Here, abs(-43) returns 43 because 43 is the absolute value of -43.
    abs(2):
        Similarly, abs(2) returns 2 because 2 is already positive.

* Using bool() Function:
    bool(0):
        The bool() function converts a value to a Boolean (True or False).
        0 is considered False in a Boolean context.
    bool(1):
        Any non-zero integer is considered True.
        Here, 1 converts to True.
    bool(45):
        Similarly, any non-zero integer, including 45, converts to True.
    bool("asd"):
        Non-empty strings are considered True.
         Here, the string "asd" converts to True.
    bool(None):
        None is a special constant in Python that represents the absence of a value or a null value.
        None converts to False.