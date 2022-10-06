# Multiplying-two-matrix

## AIM:
To multiply two arrays using numpy.



## ALGORITHM:

### Step 1:
Import numpy.

### Step 2:
Get the input as array.

### Step 3:
Append it to a empty list.

### Step 4:
Multiply the two arrays.

### Step 5:
Print it.


## PROGRAM: 
```python
Name:J.P.Aravind samy
reg.no:22005040

import numpy as np
l1,l2=[],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
result=value1*value2
print("Product of two arrays is:",result)

```

## OUTPUT:
![output](/multiply.png)

## RESULT:
Multiplying of two arrays using numpy has been successfully done.


