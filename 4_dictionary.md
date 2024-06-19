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