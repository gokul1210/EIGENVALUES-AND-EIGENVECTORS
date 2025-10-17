# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the necessary library, numpy, for matrix operations.

### Step 2:
Define the given matrix using the numpy.array() method.

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
Display the eigenvalues and eigenvectors using the print() function.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: GOKUL S
#RegisterNumber:212224230075

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
<img width="1340" height="892" alt="image" src="https://github.com/user-attachments/assets/361a8b8a-6aeb-4738-8e28-93f256dc3037" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
