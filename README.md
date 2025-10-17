# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable
4. print the variable 'X

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: porkodi B
RegisterNumber:212224240114
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
Developed by: porkodi B
RegisterNumber:212224240114
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
1
<img width="1264" height="563" alt="Screenshot 2025-10-17 194921" src="https://github.com/user-attachments/assets/b3bbf1f1-1dce-46dc-895f-5a7bc8a95862" />

2
<img width="862" height="368" alt="Screenshot 2025-10-17 195015" src="https://github.com/user-attachments/assets/f92870c6-4304-4cd6-8d85-fc8d1942e937" />





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

