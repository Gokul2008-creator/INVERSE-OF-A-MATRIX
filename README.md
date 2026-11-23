# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4:
 End the program


## Program:
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
r=np.linalg.inv(A)
print(r)
## Output:

<img width="1142" height="685" alt="image" src="https://github.com/user-attachments/assets/3071bd75-7a4e-4a0c-9b50-568b94156081" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

