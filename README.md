# Inverse-of-matrix

## AIM:
To find the invers of nested array using python.

## ALGORITHM:
### Step 1:

import numpy as np

### Step 2:

Get the input in integer.

### Step 3:

Append the list using for loop.

### Step 4:

For finding inverse we give inverse =np.linalg.inv.

### Step 5:

Now print(inverse).

## PROGRAM:
```
import numpy as np
l1,l2=[],[]
r,c=int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input())
        l1.append(num)
    l2.append(l1)
    l1=[]
print(l2)
value1=np.array(l2)
inverse=np.linalg.inv(value1)
print(inverse)
```
## OUTPUT:
![Output](.//outimg.png)

## RESULT:

Successfully finded the inverse of array using python.
