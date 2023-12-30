# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Define the package as scipy.linalg import lu.
## Step 2:
Get input from user and print L and U matrix by 'print'
## Step 3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
## Step 4:
print the variable 'X'

## Program:
(i) To find the L and U matrix
```
'''
Program to find L and U matrix using LU decomposition.
Developed by: Priyadharshini.P
RegisterNumber: 23013604
'''
# To print L and U matrix 
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''
Program to solve a matrix using LU decomposition.
Developed by: Priyadharshini.P 
RegisterNumber: 23013604
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
![image](https://github.com/priyadharshini210/LU-Decomposition/assets/148514638/21160b13-39d6-4e8e-ba88-4d48c42a3613)
![image](https://github.com/priyadharshini210/LU-Decomposition/assets/148514638/ed764a81-77c0-49c3-a276-b74adcd9e908)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

