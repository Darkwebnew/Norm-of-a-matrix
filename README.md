# EX 07 Norm of a matrix
## Date: 03.10.2023
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
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: yourname
RegisterNumber: 
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
```
# Infinity Norm of a Matrix
```
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-10-05 171534](https://github.com/Darkwebnew/Norm-of-a-matrix/assets/143114486/6fb51d8a-54c5-4d54-8bb1-49847ad06ec0)
### 2-Norm of a Matrix
![Screenshot 2023-10-05 171834](https://github.com/Darkwebnew/Norm-of-a-matrix/assets/143114486/5d5e91e3-29cf-4f8b-b1d6-34e09a4377b5)
### Infinity Norm of a Matrix
![Screenshot 2023-10-05 171729](https://github.com/Darkwebnew/Norm-of-a-matrix/assets/143114486/37be5e11-cc58-4b45-9bdc-2c044fd25ec2)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
