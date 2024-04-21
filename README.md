# EIGENVALUES-AND-EIGENVECTORS
## Aim:
## DATE: 23.03.2024
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
```
#program to find the eigen values and associated eigenvectors for the matrix [2,2],[1,3]

#prgram to find the eigen values and associated eigen vectorsfor the given matrix 
#devoleped by : poovarasu
#registerNumber:2305002017
import numpy as np
a=np.array([[2,2],[1,3]])
e,ev=np.linalg.eig(a)
print("the eigen values are",e,"\nthe eigen vectors are\n",ev)
```

## Output:
![4](https://github.com/Poovarasu8/EIGENVALUES-AND-EIGENVECTORS/assets/155505954/096ea8e6-fa12-4b3a-9f23-6314bb788742)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
