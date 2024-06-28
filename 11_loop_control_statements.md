### 1. break Statement

```
counter = 0
while counter < 100:
    if counter == 4:
        break
    print(counter)
    counter = counter + 1
```

Explanation:
    The while loop runs as long as counter is less than 100.
    Inside the loop, it checks if counter is equal to 4.
    If counter is 4, the break statement is executed, which immediately exits the loop.
    Otherwise, it prints the current value of counter and increments counter by 1.
    The loop stops when counter reaches 4.

```
Output:

0
1
2
3
```

### 2. pass Statement

```
counter = 0
while counter < 100:
    if counter == 4:
        break
    else:
        pass
    print(counter)
    counter = counter + 1
```

Explanation:
    The while loop runs as long as counter is less than 100.
    Inside the loop, it checks if counter is equal to 4.
    If counter is 4, the break statement is executed, which immediately exits the loop.
    The else: pass statement is a placeholder and does nothing.
    It prints the current value of counter and increments counter by 1.
    The loop stops when counter reaches 4.

```
Output:

0
1
2
3
```

### 3. continue Statement in a String Loop

```
for i in "Python":
    if i == "h":
        continue
    print(i)
```

Explanation:
    The for loop iterates over each character in the string "Python".
    Inside the loop, it checks if the current character i is "h".
    If i is "h", the continue statement is executed, which skips the rest of the loop body and moves to the next iteration.
    Otherwise, it prints the current character i.

```
Output:

P
y
t
o
n
```

### 4. continue Statement in a Range Loop

```
for i in range(0, 5):
    if i < 2:
        continue
    print(i)

Explanation:
    The for loop iterates over the numbers from 0 to 4.
    Inside the loop, it checks if the current number i is less than 2.
    If i is less than 2, the continue statement is executed, which skips the rest of the loop body and moves to the next iteration.
    Otherwise, it prints the current number i.

```
Output:

2
3
4
```