# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1: Import numpy library using import statement.

Step 2: From scipy package import lu().

Step 3: Get input from user and pass it as an array.

Step 4: Get P, L, U matrix using lu()

Step 5: Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SANJAY S
RegisterNumber: 212222230132

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SANJAY  S
RegisterNumber: 212222230132

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = eval(input())
b = eval(input())
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)
*/
```

## Output:
![image](https://github.com/22002102/LU-Decomposition/assets/119091638/77069f3c-00d6-457a-a215-3d17ad4d964c)




![image](https://github.com/22002102/LU-Decomposition/assets/119091638/10e2c6e8-1d7a-4bd8-95b5-2d7d4dd2361f)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

