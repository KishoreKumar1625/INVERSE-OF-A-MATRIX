# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: 
### Step 4: 

## Program:

#Program to find the inverse of a matrix.

#Developed by: Kishore kumar P

#RegisterNumber:26002452

import os

os.environ["OPENBLAS_NUM_THREADS"] = "1"

import numpy as np

A = np.array([[6, 2, 3],
              [3, 1, 1],
              [10, 3, 4]])

C = np.linalg.inv(A)

print(C)

## Output:
## Result:
Thus the inverse of given matrix is successfully solved using python program

