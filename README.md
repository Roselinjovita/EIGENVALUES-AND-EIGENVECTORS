# EIGENVALUES-AND-EIGENVECTORS

## Aim:

To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:

1. 	Hardware – PCs

2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 :
write a python program to find the Eigenvalues and Eigen Vectors

### Step 2:
Get the input values

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by:S.Roselin mary jovita
#RegisterNumber:212222230122
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are",evalues,"and Eigen Vectors are",evector)
```

## Output:




## ![eigen](https://user-images.githubusercontent.com/119104296/227249226-b0b745c1-053b-485b-8bc6-8571b53e335e.png)
Result:

Thus the Eigenvalue and Eigenvector is successfully solved using python program
