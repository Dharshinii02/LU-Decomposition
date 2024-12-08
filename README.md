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

```

Developed by: dharshini j
RegisterNumber: 24900678
*/
```

## Output:

![Screenshot 2024-12-08 232235](https://github.com/user-attachments/assets/f911be3f-cd87-402d-ad07-36de117fb33d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

