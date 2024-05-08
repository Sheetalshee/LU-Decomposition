# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. start the program
2. write the code appropirately 
3. check the code
4. run the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:SHEETAL.R 
RegisterNumber: 212223230206
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix

'''Program to find L and U matrix using LU decomposition.
Developed by: SHEETAL 
RegisterNumber: 212223230206
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

## Output:
![image](https://github.com/Sheetalshee/LU-Decomposition/assets/144979107/6a09f0d4-c5a7-4d04-a25c-a613720011be)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

