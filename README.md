# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import numpy as np.
### Step 2: 
Creates a 3x3 matrix.
### Step 3:
 Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
The variable rank holds calculated rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: 
#RegisterNumber:
import numpy as np
my_matrix=np.array([[3,2,5],[1,1,2],[3,3,6]])
rank=np.linalg.matrix_rank(my_matrix)
print(rank)
```
## Output:
![Alt text](image.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

