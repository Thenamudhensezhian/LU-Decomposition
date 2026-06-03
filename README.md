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
'''Program to find L and U matrix using LU decomposition.
Developed by: THENAMUDHEN S
RegisterNumber: 212225040471
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
matrix = np.array(eval(input()))
P,L,U=lu(matrix)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: THENAMUDHEN S
RegisterNumber: 212225040471
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix= np.array(eval(input()))
constant= np.array(eval(input()))
piv,lu= lu_factor(matrix)
result= lu_solve((piv,lu),constant)
print(result)
```

## Output:
<img width="820" height="693" alt="image" src="https://github.com/user-attachments/assets/ae27f4db-4d54-4543-b4ad-ecf790c5a22d" />
<img width="944" height="712" alt="image" src="https://github.com/user-attachments/assets/66f521b4-596a-457b-99e8-6e3565099f93" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

