# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
 1. Take matrix input from the user and convert it to a NumPy array.
 
 2.Apply LU decomposition using scipy.linalg.lu() to get P, L, and U.

 3.Extract the L (lower) and U (upper) triangular matrices.

 4.Print the L and U matrices.


## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: vutukuri sai kumar Reddy
RegisterNumber:212224230307
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U) 

```
## Algorithm
1.Input matrix A and vector/matrix B from the user.

2.Perform LU factorization of matrix A using lu_factor().

3.Solve the system of equations AX = B using lu_solve().

4.Print the solution vector/matrix X.

(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by:vutukuri sai kumar Reddy
RegisterNumber: 212224230307
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
PV,LU=lu_factor(A)
result=lu_solve((PV,LU),B)
print(result)
```

## Output:
## (i) To find the L and U matrix:
![image](https://github.com/user-attachments/assets/0ca6ee6f-677a-4b53-a243-12d00cec2ccf)
## (ii) To find the LU Decomposition of a matrix
![image](https://github.com/user-attachments/assets/c957dc35-a633-4b4c-8263-077001d712a7)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

