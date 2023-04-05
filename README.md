# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
import numpy libary 
### Step 2: 
Assign a variable A
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
import numpy as np
A=np.array([[2,2],[1,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```
## Output:
![image](https://user-images.githubusercontent.com/119559022/229991551-fdd283f2-831c-436f-95c4-3656922a5e32.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
