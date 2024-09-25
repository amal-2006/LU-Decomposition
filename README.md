## DATE:
## EX NO 5: LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.

2. Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable. 

4. Print the variable 'x'. 

## Program:
(i) To find the L and U matrix


```
Developed by: AMALJOSH MAADHAV J
RegisterNumber: 212223230012
```
```

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix

```

Developed by: AMALJOSH MAADHAV J
RegisterNumber:  212223230012

```
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)

```

## Output:
### Output 1-
![image](https://github.com/user-attachments/assets/2d59c24b-39e2-4cbb-a3ee-719ebffc2269)

### Output 2-
![image](https://github.com/user-attachments/assets/e228ca2b-3f4d-43fe-a761-12f889723452)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

