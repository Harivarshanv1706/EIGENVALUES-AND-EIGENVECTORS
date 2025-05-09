# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start 
### Step 2: Import NumPy, Define the Matrix
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the Results

## Program:
```
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
eigen_values,eigen_vector=np.linalg.eig(a)
print(f"Eigen values are {eigen_values} and Eigen Vectors are {eigen_vector}")
```
## Output:

![Screenshot 2025-05-09 204851](https://github.com/user-attachments/assets/d6578416-f0f4-4ff0-b384-31cdea2ca83d)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
