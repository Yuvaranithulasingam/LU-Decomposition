# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: Yuvarani T
RegisterNumber: 22009033
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)
/*
Program to find the LU Decomposition of a matrix.
Developed by: Yuvarani T
RegisterNumber: 22009033
*/
```

## Output:
![lu decomposition]()

![LU Decomposition 1](https://user-images.githubusercontent.com/121418522/212944761-170c762e-0bd6-4c47-a00f-6bd7ee4d6122.png)

![lu decomposition 2](https://user-images.githubusercontent.com/121418522/212944831-1270e5c0-80a5-4d33-b42a-d5663cc22902.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

