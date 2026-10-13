# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : start the program
### Step 2: import numpy as np and define a matrix A
### Step 3: calculate the inverse of matrix A using np.linalg.inv(a)
### Step 4: print the inverse of matrix

## Program:
#Program to find the inverse of a matrix.
#Developed by: Yuvethika V
#RegisterNumber:26016105
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)
## Output:
<img width="601" height="587" alt="{24F1CFED-A0DD-4EA9-945D-38A109041B09}" src="https://github.com/user-attachments/assets/6602639d-c088-40ef-bb71-e8c2f7e95b9d" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

