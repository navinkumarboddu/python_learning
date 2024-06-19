### Creating a String List:
```markdown
shoppingList = "egg, carrots, milk, cherries, apples"
# Creates a string containing a list of items separated by commas.
```

### Displaying the String List:
```markdown
shoppingList
'egg, carrots, milk, cherries, apples'
# This displays the string representation of the shopping list.
```

### Creating a List of Items:
```
shoppingList2 = ["eggs", "carrots", "milk", "cherries", "apples"]
# This line creates a list (array) where each item is an element of the list.
```

### Displaying the List:
```
shoppingList2
['eggs', 'carrots', 'milk', 'cherries', 'apples']
# This displays the list of items.
```

### Accessing an Item by Index:
```
shoppingList2[2]
'milk'
# This retrieves the item at index 2 (the third item) from the list.
```

### Displaying the List Again:
```
shoppingList2
['eggs', 'carrots', 'milk', 'cherries', 'apples']
# This displays the list to confirm it remains unchanged.
```

### Accessing Another Item by Index:
```
shoppingList2[3]
'cherries'
# This retrieves the item at index 3 (the fourth item) from the list.
```

### Modifying an Item in the List:
```
shoppingList2[2] = "chocos"
# This changes the item at index 2 (the third item) to "chocos".
```

### Displaying the Updated Item:
```
shoppingList2[2]
'chocos'
# This retrieves the updated item at index 2.
```

### Displaying the Updated List:
```
shoppingList2
['eggs', 'carrots', 'chocos', 'cherries', 'apples']
# This displays the entire list to show the modification.
```

## List Functions

### Concatenate Arrays:
```
array1 = [23, 54, 64]
# Creates a list named array1 containing the integers 23, 54, and 64.

array2 = [43, 23]
# Creates a list named array2 containing the integers 43 and 23.

array3 = array1 + array2
# Concatenates array1 and array2 into a new list named array3.

array3
[23, 54, 64, 43, 23]
# Outputs the concatenated list array3.
```

### Length of Arrays:
```
len(array3)
5
# Calculates and outputs the length of array3, which is 5.
```

### Max, Min of Array
```
numArray = [26, 75, 1004, 1, -5]
# Creates a list named numArray containing the integers 26, 75, 1004, 1, and -5.

max(numArray)
1004
# Finds and outputs the maximum value in numArray, which is 1004.

min(numArray)
-5
# Finds and outputs the minimum value in numArray, which is -5.
```

### Append to Array
```
numArray.append(2424)
# Appends the integer 2424 to the end of numArray.

numArray
[26, 75, 1004, 1, -5, 2424]
# Outputs the updated numArray list after appending 2424.
```

### Count of item
```
numArray.count(-5)
1
# Counts and outputs the number of occurrences of the integer -5 in numArray, which is 1.
```