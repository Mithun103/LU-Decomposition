# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.import numpy as np
2.get the input from user
3.use array function
4.assign variables to array function to get the result. 

## Program:
(i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by:m.s.mithun
RegisterNumber:22008364
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![Screenshot_20230122_123124](https://user-images.githubusercontent.com/118344695/213905357-18fb129d-9dc7-4c8a-81c0-6c772415715e.png)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

