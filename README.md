# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program and import the required library (numpy).
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: end the results

## Program:

```
#Program to find the inverse of a matrix.
#Developed by: 
#RegisterNumber:

import numpy as np
A=np.array([
    [6,2,3],
    [3,1,1],
    [10,3,4]
    ])
x=np.linalg.inv(A)
print(x)
```

## Output:

<img width="723" height="218" alt="Screenshot 2026-02-05 195631" src="https://github.com/user-attachments/assets/3a206cb7-6a6c-42ac-92a4-373afa4c10f2" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

