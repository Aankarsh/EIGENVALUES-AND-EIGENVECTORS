# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : import numpy
### Step 2: take a variable and assign the given matrix in np.array
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: print the result

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: AANKARSH
#RegisterNumber:24013602
import numpy as np
mat=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
e_values,e_vectors=np.linalg.eig(mat)
print(f"Eigen values are {e_values} and Eigen Vectors are {e_vectors}")
```

## Output:
![image](https://github.com/user-attachments/assets/99b5eebf-9000-41aa-97a9-c113a6a8543d)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
