### Creating a Dictionary:
```markdown
students = {"Eric": 1, "Bob": 2, "Tim": 3}
# Creates a dictionary named students with keys "Eric", "Bob", and "Tim" and corresponding values 1, 2, and 3.

students
{'Eric': 1, 'Bob': 2, 'Tim': 3}
# Outputs the students dictionary.
```

### Access the items
```
students["Bob"]
2
# Accesses and outputs the value associated with the key "Bob", which is 2.

students["Tim"]
3
# Accesses and outputs the value associated with the key "Tim", which is 3.
```

### Update the items in dictionary
```
students["Tim"] = 4
# Updates the value associated with the key "Tim" to 4.

students["Tim"]
4
# Accesses and outputs the updated value associated with the key "Tim", which is now 4.
```

### Delete the items in dictionary
```
del students["Bob"]
# Deletes the key-value pair for "Bob" from the students dictionary.

students
{'Eric': 1, 'Tim': 4}
# Outputs the updated students dictionary after deleting the key "Bob".
```

### Clear Dictionary
```
students = {"John": 15, "Marc": 24, "Bujji": 15}
# Creates a dictionary named students with keys "John", "Marc", and "Bujji" and corresponding values 15, 24, and 15.

students
{'John': 15, 'Marc': 24, 'Bujji': 15}
# Outputs the students dictionary.

students.clear()
# Clears all key-value pairs from the students dictionary.

students
{}
# Outputs the now-empty students dictionary.
```

### Delete Dictionary
```
del students
# Deletes the students dictionary.

students
Traceback (most recent call last):
File "<stdin>", line 1, in <module>
NameError: name 'students' is not defined
# Raises an error because students has been deleted and no longer exists.
```

### Length of Dictionary
```
students = {"John": 15, "Marc": 24, "Bujji": 15}
# Recreates the students dictionary with the original key-value pairs.

len(students)
3
# Calculates and outputs the number of key-value pairs in the students dictionary, which is 3.
```

### Get keys and valyes of Dictionary
```
students.keys()
dict_keys(['John', 'Marc', 'Bujji'])
# Outputs the keys of the students dictionary.

students.values()
dict_values([15, 24, 15])
# Outputs the values of the students dictionary.
```

### Append/Update two Dictionaries
```
students2 = {"Asvath": 15, "Sum": 80, "Yaskin": 15}
# Creates another dictionary named students2 with keys "Asvath", "Sum", and "Yaskin" and corresponding values 15, 80, and 15.

students.update(students2)
# Updates the students dictionary with key-value pairs from students2.

students
{'John': 15, 'Marc': 24, 'Bujji': 15, 'Asvath': 15, 'Sum': 80, 'Yaskin': 15}
# Outputs the updated students dictionary which now includes key-value pairs from students2.
```