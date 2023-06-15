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
```
(i) To find the L and U matrix:

Developed by: SANJAY S
RegisterNumber: 212222230132
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)








(ii) To find the LU Decomposition of a matrix:

Developed by: SANJAY S
RegisterNumber: 212222230132
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)


```


## Output:

![image](https://github.com/22002102/LU-Decomposition/assets/119091638/e81786f7-593d-496d-9aeb-d51ede785214)




![image](https://github.com/22002102/LU-Decomposition/assets/119091638/f70c00a9-85d8-43c7-81cf-4b5174d758bc)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

