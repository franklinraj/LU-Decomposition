# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
1. start the program
2. use numpy and sys packages 
3. use nested loops to loop through each row and column 
4. end the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:FRANKLIN RAJ G 
RegisterNumber:23001518
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:FRANKLIN RAJ G
RegisterNumber:23001518
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
 
*/
```

## Output:
![Screenshot 2023-12-21 142641](https://github.com/franklinraj/LU-Decomposition/assets/148993740/c90b46f8-292c-4dce-b266-4edfc32ce61f)
![Screenshot 2023-12-21 142733](https://github.com/franklinraj/LU-Decomposition/assets/148993740/053df4cf-3259-4ca6-bb83-62594f226393)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

