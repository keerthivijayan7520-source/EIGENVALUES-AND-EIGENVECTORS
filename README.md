-#EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Start the programe.
### Step 2: Impot the NumPy library and create the given matrix using np.array().
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:Display the eigenvalues and eigenvectors and stop the programe. 

## Program:
### Program to find the eigen values and eigen vectors.
### Developed by:Keerthi.V
### RegisterNumber:26010139
### import os
### os.environ["OPENBLAS_NUM_THREADS"]="1"
### import numpy as np
### A=np.array([[4,2],[2,4]])
### values,Vectors=np.linalg.eig(A)
### print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:
<img width="1073" height="812" alt="image" src="https://github.com/user-attachments/assets/4636b84a-db84-40f8-a9f6-a8c358e91fd4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
