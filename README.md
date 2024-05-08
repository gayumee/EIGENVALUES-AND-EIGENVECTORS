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

![Screenshot 2024-05-08 200949](https://github.com/gayumee/EIGENVALUES-AND-EIGENVECTORS/assets/149037327/06d4baaa-7c6c-4adb-a688-786e5cf2d9ba)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
