# EX07 Norm of a matrix
NAME:RAMYA.P

REGISTER NUMBER:212223240137

DEPARTMENT:AIML

## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
        2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Program:
# program to find 1-norm of the matrix
```
program to find 1-norm of the matrix
Developed by:RAMYA.P
Register number:212223240137

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Program to find 2-norm of a matrix.
'''
Program to find 2-norm of a matrix.
Developed by: RAMYA.P
RegisterNumber: 212223240137

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Program to find infinity-norm of a matrix
```
Program to find infinity-norm of a matrix
Developed by: RAMYA.P
RegisterNumber: 212223240137

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-05 172749](https://github.com/23014107/Norm-of-a-matrix/assets/151625620/5f17b3a9-6806-45fd-b067-628ea9585df9)

### 2-Norm of a Matrix
![Screenshot 2024-05-05 172837](https://github.com/23014107/Norm-of-a-matrix/assets/151625620/4310b757-6bc4-4f6f-8334-c5ccb241f4e9)

### Infinity Norm of a Matrix
![Screenshot 2024-05-05 172943](https://github.com/23014107/Norm-of-a-matrix/assets/151625620/8e82341a-2524-47dc-943d-6bfcfabcaa4b)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
