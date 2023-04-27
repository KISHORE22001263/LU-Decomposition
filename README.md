# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
## STEP 1
Import numpy library using import statement. 
## STEP 2
From scipy package import lu().
## STEP 3
Get input from user and pass it as an array.
## STEP 4 
Get P, L, U matrix using lu()
## STEP 5
Print L and U matrix
## Program:
## (i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by:KISHORE.B 
RegisterNumber:212222110020
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
## (ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: KISHORE.B 
RegisterNumber:212222110020
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b=np.array([4, 5, 7])
lu,p=lu_factor(arr)
res=lu_solve((lu,p),b)
print(res)
```

## Output:
## L AND U MATRIX
![Screenshot 2023-04-27 090156](https://user-images.githubusercontent.com/121484538/234754053-4931eae2-9cee-41ea-979e-acbe2bb87610.png)
## LU DECOMPOSITION OF MATRIX
![Screenshot 2023-04-27 090216](https://user-images.githubusercontent.com/121484538/234754175-f1950939-2e57-423e-b3fa-ebd4d80575c2.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
