# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy as np

2. Import library called 'scipy' to solve the lu decomposition.

3.Import lu_factor and lu_solve libraries. 

4.Get the input to solve the lu decomposition.

5. Print the result obtained.

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Meetha Prabhu
RegisterNumber: 212222240065

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Meetha Prabhu
RegisterNumber: 212222240065

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![image](https://user-images.githubusercontent.com/119401038/232712379-0f38af5d-66bd-4083-9db0-41a51455c664.png)

![image](https://user-images.githubusercontent.com/119401038/232712488-c1a8c6bc-beda-4464-91d0-9f6449991c20.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

