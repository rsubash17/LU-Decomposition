# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: SUBASH R
RegisterNumber: 23003821
#To print L and U matrix
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
Developed by: SUBASH R
RegisterNumber: 23003821
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b =np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)

*/
```

## Output:
![lu decomposition]()

![Screenshot 2023-12-21 213724](https://github.com/rsubash17/LU-Decomposition/assets/147139828/5cfe95a9-e0cf-45d6-9a41-c9a4b795946b)

![Screenshot 2023-12-21 213853](https://github.com/rsubash17/LU-Decomposition/assets/147139828/85d5bc1b-4b3d-4bcd-b4a8-44284d5d68fe)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

