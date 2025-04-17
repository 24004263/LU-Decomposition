# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy module to use the built-in functions for calculation.
2. Prepare the lists from each linear equations and assign in np.array().
3. Using the np.linalg.solve(), we can find the solutions.
4. nd the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: pramisha
RegisterNumber: 212224230203
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: pramisha
RegisterNumber: 212224230203
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
pv,lu=lu_factor(A)
result=lu_solve((pv,lu),B)
print(result)
*/
```

## output:
![alt text](<Screenshot 2025-04-10 143852-1.png>)
![alt text](<Screenshot 2025-04-10 143914.png>)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

