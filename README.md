# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.STEP1:Import the numpy module to use the built-in functions for calculation 
2.STEP2:Prepare the lists from each equation and assign in np.array 
3.STEP3:Using the np.linalg.matrix_rank(),we can find the rank of the given matrix 
4.STEP4:end the program 

## Program:
(i) To find the L and U matrix

```
Program to find L and U matrix using LU decomposition.
Developed by:lavanya R
RegisterNumber:25017651 

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: lavanya R
RegisterNumber:25017651 

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```

## Output:
<img width="1232" height="577" alt="Screenshot 2025-11-23 145017" src="https://github.com/user-attachments/assets/be366948-5bbe-4a8f-81ef-4d740a78eba7" />
<img width="1213" height="794" alt="Screenshot 2025-11-23 145058" src="https://github.com/user-attachments/assets/10da3406-ee28-4aa9-a978-e1a06cfbb1c2" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

