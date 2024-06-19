### Basic Arithmetic Operations
```markdown
>>> age1 = 14
>>> age2 = 40
>>> age3 = age1 + age2
>>> age3
54

>>> age1 - age2
-26

>>> age1 / age2
0.35

>>> age1 * age2
560

>>> age1 % age2
14

```

### Basic String Operations
```markdown
>>> myName = "Avinash"
>>> firstName = "Avi"
>>> secondName = "Jain"

>>> fullName = firstName + secondName
>>> fullName
'AviJain'

>>> fullName = firstName + " " + secondName
>>> fullName
'Avi Jain'

>>> random = "Avinash adasdadaddadaasdadd"
>>> random[10]
'a'

>>> random[9]
'd'

>>> random[0, 8]
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: string indices must be integers

>>> random[0:8]
'Avinash '

>>> random[0:7]
'Avinash'

>>> random[3:]
'nash adasdadaddadaasdadd'

```