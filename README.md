# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program
### Step 2: Enter the values
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Stop the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Aavula Tharun 
#RegisterNumber:21003406
import numpy as np
A = np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:
![output](https://github.com/AavulaTharun/EIGENVALUES-AND-EIGENVECTORS/blob/main/eigen.JPG?raw=true)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
