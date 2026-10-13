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

## Output:<img width="1274" height="654" alt="Screenshot 2026-10-13 204540" src="https://github.com/user-attachments/assets/2e8e9c25-9076-410a-bcf8-7c1714307e35" />
<img width="1272" height="214" alt="Screenshot 2026-10-13 204552" src="https://github.com/user-attachments/assets/ab87f3d4-81d8-4c23-9c21-8b3ecf16289a" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

