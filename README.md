# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
# program 1
# 1.Import numpy library
# 2.Import lu function from scipy library.
# 3.Solve LU decompostion using lu() function
# 4.print the value

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
## Algorithm.
## Program 2
# 1. Import numpy
# 2.From scipy.linalg import lu,lu_factor,lu_solve respectively
# 3.Get the input of matrix values from user using eval
# 4.Print and solce LU decomposition using lu_solve() function

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

