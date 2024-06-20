### Creating a tuple
```
tup1 = ("Maths", 23, "Dogs")
# Creates a tuple named tup1 containing the elements "Maths", 23, and "Dogs".

tup1.append("asd")
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
AttributeError: 'tuple' object has no attribute 'append'
# Raises an AttributeError because tuples are immutable and do not support the append method.

del tup1["Maths"]
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
TypeError: 'tuple' object does not support item deletion
# Raises a TypeError because tuples do not support item deletion by key.

tup1 = ("Cheese")
# Reassigns tup1 to the string "Cheese".

tup1
'Cheese'
# Outputs the string "Cheese" because tup1 is now a string.

tup1 = ("Maths", 23, "Dogs")
# Reassigns tup1 back to a tuple with the original elements "Maths", 23, and "Dogs".

tup1
('Maths', 23, 'Dogs')
# Outputs the tuple tup1.
```

### Access the items
```
tup1[0]
'Maths'
# Accesses and outputs the first element of the tuple, which is "Maths".

tup1[1]
23
# Accesses and outputs the second element of the tuple, which is 23.

tup1[2]
'Dogs'
# Accesses and outputs the third element of the tuple, which is "Dogs".
```

### Get items using range
```
tup1[0:2]
('Maths', 23)
# Outputs a slice of the tuple from index 0 to index 2 (exclusive), which includes "Maths" and 23.

tup1[0:3]
('Maths', 23, 'Dogs')
# Outputs a slice of the tuple from index 0 to index 3 (exclusive), which includes "Maths", 23, and "Dogs".
```

### Delete tuple
```
del tup1
# Deletes the tuple tup1.
```