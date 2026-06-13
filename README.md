# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program
## Program:
```
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[6,2,3],[3,1,1],[10,3,4]])
inverse=np.linalg.inv(matrix)
print(inverse)
```
## Output:
<img width="1376" height="752" alt="image" src="https://github.com/user-attachments/assets/f733d7b4-ea9d-4c3b-ae15-7e1727e581bf" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

