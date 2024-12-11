# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy and initialize the L and U matrices
2. For each row, eliminate variables below the pivot
3. Update L and U matrices and return
4. End the program

## Program:


```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)


import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(A)
X= lu_solve((lu,piv),b)
print(X)




```

## Output:

![Screenshot 2024-12-11 080717](https://github.com/user-attachments/assets/43b124e8-f647-47c1-97a0-c1d2d1baaac0)
![Screenshot 2024-12-11 080732](https://github.com/user-attachments/assets/bcb5d4a2-4d74-4005-869b-92db4bc1c717)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

