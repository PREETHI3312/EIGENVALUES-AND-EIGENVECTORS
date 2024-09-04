## DATE:
## EXP 4 EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: get the input from user
## Step 2: import math and initialise the two values
## Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.
## Step 4:print the values in format

## Program:
```import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vect=np.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vect)
```


## Output:
![image](https://github.com/user-attachments/assets/92169cda-8ad7-49d6-8c61-164ecb612a89)
![image](https://github.com/user-attachments/assets/4797f6fc-6c3d-48f6-9656-31f8d7685138)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
