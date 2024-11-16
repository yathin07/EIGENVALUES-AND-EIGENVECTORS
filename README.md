# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
    import numpy as np
    a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
    values,vector=np.linalg.eig(a)
    print(f"Eigen values are {values} and Eigen Vectors are {vector}")

## Output:
![image](https://github.com/user-attachments/assets/dc2bf38d-2465-4078-aa8f-1aa6c16f101d)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
