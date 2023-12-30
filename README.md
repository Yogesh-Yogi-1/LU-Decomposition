# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable 'X' 
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: V. Yogesh
RegisterNumber: 212223230250
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: V. Yogesh
RegisterNumber: 212223230250
*/
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu, piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
### For L and U matrix
![Screenshot 2023-12-30 134251](https://github.com/Yogesh-Yogi-1/LU-Decomposition/assets/148514598/555ec6b5-3590-4f47-bb20-099ef8a3a0e7)

### To solve a matrix
![Screenshot 2023-12-30 134333](https://github.com/Yogesh-Yogi-1/LU-Decomposition/assets/148514598/9e73efee-556a-4a77-9e07-9cab7c86b533)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

