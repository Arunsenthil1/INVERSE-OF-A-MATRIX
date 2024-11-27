# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the inverse of the given matrix
### Step 4: End the program

## Program:
```
import numpy as np

# Define the matrix
matrix = np.array([[1, 0, 3],
                   [-1, 2, -2],
                   [2, 3, -1]])

# Compute the inverse
try:
    inverse_matrix = np.linalg.inv(matrix)
    print(inverse_matrix)
except np.linalg.LinAlgError:
    print("The matrix is singular and cannot be inverted.")
```
## Output:
![Screenshot 2024-11-27 214851](https://github.com/user-attachments/assets/0044195b-6421-465e-8ed3-d2bcb82b0b09)

## Result:
Thus the inverse of given matrix is successfully solved using python program

