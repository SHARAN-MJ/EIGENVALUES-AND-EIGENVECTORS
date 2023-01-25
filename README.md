# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
import numpy as np
a=np.array([[2,2],[1,3]])
value,vector=np.linalg.eig(a)
print(f'Eigen values are {value} and Eigen Vectors are {vector}')
## Output:
![output](./Screenshot_20230125_033939.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
