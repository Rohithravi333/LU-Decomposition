# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step 1:
Import numpy library using import statement.

## Step 2:
From scipy package import lu().

## Step 3:
Get input from user and pass it as an array.

## Step 4:
Get P, L, U matrix using lu()

## Step 5:
Print L and U matrix

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: rohith r
RegisterNumber: 212222230121
*/

# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P, L, U = lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: rohith r
RegisterNumber: 212222230121
*/
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, pivot = lu_factor(A)
x = lu_solve((lu,pivot),B)
print(x)


```

## Output:
##  L and U matrix
<img width="574" alt="5a" src="https://github.com/Rohithravi333/LU-Decomposition/assets/119394126/d7e385fe-ad87-4bcf-b8df-b361eb671ecb">

### LU Decomposition of a matrix

<img width="502" alt="5b" src="https://github.com/Rohithravi333/LU-Decomposition/assets/119394126/d5714002-2da5-4728-a9c2-abf394085b7a">



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

