# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import numpy as np package
### Step 2:
Declare the values and store it in a varialbe
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: T. Gayathri
#RegisterNumber: 212223100007

import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,Vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))
```
## Output:
```
Eigen values are [-3.  5. -3.] and Eigen Vectors are [[-0.95257934  0.40824829 -0.02296692]
 [ 0.27216553  0.81649658  0.83534731]
 [-0.13608276 -0.40824829  0.54924256]]
```
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
