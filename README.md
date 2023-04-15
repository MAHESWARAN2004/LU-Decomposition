# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: MAHESWARAN.K
RegisterNumber: 212222110023
'''

import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: MAHESWARAN.K
RegisterNumber: 212222110023
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=np.array([4, 5, 7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)

```

## Output:

![Ex05(A)](https://user-images.githubusercontent.com/119478181/232190749-aed3faeb-b536-425e-b8b5-258281bda797.png)
![Exp-05(B)](https://user-images.githubusercontent.com/119478181/232190757-719a047c-7a7b-4584-b55e-fe74e11ee60b.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

