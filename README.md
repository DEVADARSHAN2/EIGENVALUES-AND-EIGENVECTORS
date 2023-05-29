# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	
Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Get the input matrix from the user

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program
```
NAME : DEVADARSHAN A S
REG NO : 212222110007
```
## Program:
```
import numpy as np
a=np.array([[4,2],[2,4]])
value,vector=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(value,vector))
```

## Output:
![image](https://github.com/DEVADARSHAN2/EIGENVALUES-AND-EIGENVECTORS/assets/119432150/a8242ffb-9209-4ecd-9e7c-5665040ad02a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program.
