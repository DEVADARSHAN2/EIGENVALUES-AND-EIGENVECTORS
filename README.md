# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy as np
### Step 2: 
using array function convert the equation into matrix form .
### Step 3:
 Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix. 
## Program:
```
Program to find the eigen values and eigen vectors.
Developed by: DEVADARSHAN A S
RegisterNumber:212222110007
```
```
import numpy as np
a = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```

## Output:

![image](https://github.com/DEVADARSHAN2/EIGENVALUES-AND-EIGENVECTORS/assets/119432150/fbb97b1f-09c3-479f-ba0e-433809396bfd)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
