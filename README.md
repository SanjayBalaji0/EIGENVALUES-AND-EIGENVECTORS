# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy into the program.
### Step 2: 
Get the matrix.
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
Print the output.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sanjay Balaji S
#RegisterNumber:23005804

import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:

![image](https://github.com/SanjayBalaji0/EIGENVALUES-AND-EIGENVECTORS/assets/145533553/bb881780-f1e4-4038-b22c-5904825f7b9d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
