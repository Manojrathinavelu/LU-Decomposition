# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy.linalg import lu
3. assign the values
4. Note the output

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.

Developed by: Manoj karthik R
RegisterNumber: 22003728
'''

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Manoj karthik R 
RegisterNumber: 22003728


import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu, piv = lu_factor(A)
x= lu_solve((lu,piv),B)
print(x)

```

## Output:

![lu1](https://user-images.githubusercontent.com/119560395/214598918-9b688218-cac8-4ca0-8b2d-b2c3716b87e5.png)
![lu2](https://user-images.githubusercontent.com/119560395/214598942-f9f5a2fb-7888-48f0-b331-92ddaa964e8c.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

