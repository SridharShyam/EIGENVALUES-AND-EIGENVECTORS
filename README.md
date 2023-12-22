# EIGENVALUES-AND-EIGENVECTORS
### NAME:SHYAM S
### REF.NO: 23012478
### DEPARTMENT: AI&ML
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2:
Prepare the lists from linear equation and assign in np.array().
### Step 3:
Using the np.linalg.inv(), we can find the rank of the given matrix.
### Step 4:
End the Program.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: SHYAM S
#RegisterNumber: 23012478

import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```
## Output:
![Screenshot 2023-12-13 200709](https://github.com/SridharShyam/EIGENVALUES-AND-EIGENVECTORS/assets/144871368/86feb5ad-f6db-4ee1-840c-21f76c8a9afe)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
