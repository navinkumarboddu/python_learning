### 1. for loop with range()

```
for i in range(0, 5):
print(i)
```
Explanation:
        This loop iterates through numbers from 0 to 4 (inclusive).
        range(0, 5) generates numbers starting from 0 up to, but not including, 5.
        Each iteration, it prints the current value of i.

```
Output:

0
1
2
3
4
```

### 2. for loop iterating over a list

```
shoppingList = ["Milk", "Eggs", "Oranges"]
for i in shoppingList:
print(i)
```

Explanation:
        This loop iterates over each item (i) in the shoppingList list.
        In each iteration, it prints the current item (i).

```
Output:

Milk
Eggs
Oranges
```

### 3. for loop iterating over a set

```
tup = {2, 34, 68}
for i in tup:
print(i)
```

Explanation:
        This loop iterates over each element (i) in the set tup.
        Sets are unordered collections of unique elements, so the order of iteration is not guaranteed.
        In each iteration, it prints the current element (i).

```
Output (example):

2
34
68
```

### 4. for loop with step in range()

```
for i in range(0, 11, 2):
print(i)
```

Explanation:
        This loop iterates through numbers starting from 0 up to, but not including, 11 with a step of 2.
        It prints every second number in the range (0, 2, 4, 6, 8, 10).

```
Output:

0
2
4
6
8
10
```

### 5. for loop with negative step in range()

```
for i in range(11, 0, -1):
print(i)
```

Explanation:
        This loop iterates through numbers starting from 11 down to 1 with a step of -1 (i.e., counting backwards).
        It prints each number in descending order.

```
Output:

11
10
9
8
7
6
5
4
3
2
1
```
