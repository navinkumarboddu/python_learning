### 1. while Loop Example

```
counter = 5
while counter < 10:
print(counter)
counter = counter + 1
```
Explanation:
    Initializes the variable counter to 5.
    The while loop checks if counter is less than 10.
    If the condition is true, it executes the loop body:
        Prints the current value of counter.
        Increments counter by 1.
    The loop continues until counter is no longer less than 10.

```
Output:

5
6
7
8
9
```

### 2. Additional while Loop Example

```
index = 0
names = ["Alice", "Bob", "Charlie"]
while index < len(names):
print(names[index])
index = index + 1
```

Explanation:
    Initializes the variable index to 0.
    The while loop checks if index is less than the length of the names list.
    If the condition is true, it executes the loop body:
        Prints the element at the current index of the names list.
        Increments index by 1.
    The loop continues until index is no longer less than the length of the names list.

```
Output:

Alice
Bob
Charlie
```