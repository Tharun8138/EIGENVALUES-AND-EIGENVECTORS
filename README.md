# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm: 
### Step 1: Provide the square matrix ( A ).
### Step 2: Solve ( \det(A - \lambda I) = 0 ) to determine eigenvalues ( \lambda ).
### Step 3: Use each ( \lambda ) in ( (A - \lambda I)x = 0 ) to calculate eigenvectors ( x ).
### Step 4: Confirm ( Ax = \lambda x ) to verify your results.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Tharun.V
#RegisterNumber:212224230290

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```

## Output:

![Screenshot 2025-04-22 231854](https://github.com/user-attachments/assets/8689c92e-1bdd-4050-8f0e-6b9179987417)
![Screenshot 2025-04-22 231907](https://github.com/user-attachments/assets/d4aae87f-9191-48d7-9a52-eef50da6ed52)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
