# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 : Import NumPy as np to use its mathematical and linear algebra functions
Step 2: Create a square matrix A by placing the given values inside a nested list.
Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second
is eigenvector) of the given matrix.
Thus the Eigenvalue and Eigenvector is successfully solved using python program
Releases
No releases published
Create a new release
Step 4: Display the eigenvalues and eigenvectors as the output and end the



## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ROHITH R
#RegisterNumber: 212225230229
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = np.array([[-2, 2, -3],[2, 1, -6],[-1, -2, 0]])
eigen_values, eigen_vectors = np.linalg.eig(A)
print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)
```
## Output:
<img width="1295" height="697" alt="Screenshot 2026-05-20 141700" src="https://github.com/user-attachments/assets/f3da3f45-39b6-4e9a-9e53-5d860cac9bd4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
