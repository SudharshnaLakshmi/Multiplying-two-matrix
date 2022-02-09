# Multiplying-two-matrix

## AIM:
To write a python program for multiplying two matrix.

## EQUIPEMENT'S REQUIRED:
PC Anaconda - Python 3.7

## ALGORITHM:

### Step 1:
Use import numpy as np.
### Step 2:
Enter the input.
### Step 3:
Use append().
### Step 4:
Use * to multiply two matrix.
### Step 5:
Print.

## PROGRAM: 
```
##Developed by: Sudharshna Lakshmi.S
##Register Number: 212221230110

import numpy as np
l1,l2 = [],[]
n = int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1 = np.array(l1)
value2 = np.array(l2)
result = value1*value2
print("Product of two arrays is:",result)

```

## OUTPUT:

![Output](.//output.png)

## RESULT:
Thus the program is written to multiply two matrix.
