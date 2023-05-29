# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1:
Import numpy library using import statement.

Step 2:
From scipy package import lu().

Step 3:
Get input from user and pass it as an array.

Step 4:
Get P, L, U matrix using lu()

Step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: S Afsar jumail
RegisterNumber: 212222240004
'''
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
'''Program to solve a matrix using LU decomposition.
Developed by: S AFSAR JUMAIL 
RegisterNumber: 212222240004
'''

# To print X matrix (solution to the equations)
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
(i)
![2023-05-29 (7)](https://github.com/Afsarjumail/LU-Decomposition/assets/118343395/a55e4888-ef32-4d77-8acc-559f228ed027)
(ii)
![2023-05-29 (8)](https://github.com/Afsarjumail/LU-Decomposition/assets/118343395/d083450f-4f15-4749-b7bb-34c74e7e7247)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

