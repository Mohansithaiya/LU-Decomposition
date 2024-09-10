# DATE: 
# EX.NO.05 LU Decomposition 

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
```python
Program to find L and U matrix using LU decomposition.
Developed by: MOHAN.S
RegisterNumber: 212223240094

import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)

```

(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by: MOHAN.S
RegisterNumber: 212223240094

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:

(i) To find the L and U matrix
![Screenshot 2024-09-10 101629](https://github.com/user-attachments/assets/9549095c-09ae-4243-a6b8-41cba1d635c5)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2024-09-10 101654](https://github.com/user-attachments/assets/72344c81-4a4a-499d-8e66-0a8639d4e6bd)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

