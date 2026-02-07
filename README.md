# Exp-04---Eigen-Values-and-Eigen-Vectors
### Name: Deepadharshini T
### Reg no: 212224230052
# Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

# Equipment’s required:
Hardware – PCs
Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Read the given square matrix.
### Step 2: Import the NumPy library and store the matrix in array form.
### Step 3:Using np.linalg.eig(), obtain the eigenvalues and eigenvectors of the given matrix.
### Step 4: Display the eigenvalues and the corresponding eigenvectors.
# Program:
```

import numpy as np

A = np.array([[-2,2,-3],
              [2, 1,-6],
              [-1,-2,0]])
              
values, vectors = np.linalg.eig(A)

print("Eigen values are", values, "and Eigen Vectors are", vectors)
```
Output:

<img width="1332" height="202" alt="image" src="https://github.com/user-attachments/assets/97f47270-4ed4-45f8-9f6b-530e5a29472f" />

Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
