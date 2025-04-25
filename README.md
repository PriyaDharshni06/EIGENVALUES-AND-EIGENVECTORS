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
```python
#Program to find the eigen values and eigen vectors.
#Developed by: PRIYA DHARSHNI S
#RegisterNumber: 212224100045

import numpy as np
a= np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
![Screenshot 2025-04-25 202524](https://github.com/user-attachments/assets/862dcd71-8120-4003-8550-b3033ee2bac1)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
