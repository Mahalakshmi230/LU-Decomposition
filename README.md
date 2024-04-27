# LU Decomposition 

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
```
Program to find L and U matrix using LU decomposition.
Developed by: Mahalakshmi R
RegisterNumber: 212223230116
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: Mahalakshmi R
RegisterNumber: 212223230116
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
```

## Output:
![image](https://github.com/Mahalakshmi230/LU-Decomposition/assets/149365324/dd5af24e-5539-4cf2-ab46-b9dbd7c93003)
![Screenshot 2024-04-27 084115](https://github.com/Mahalakshmi230/LU-Decomposition/assets/149365324/47a4fe3b-1f36-4c92-9456-15f9a06c296d)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

