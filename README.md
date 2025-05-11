# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy module using import numpy as np to perform matrix operations.
### Step 2: 
Define the square matrix using np.array().
### Step 3: 
Check if the matrix is invertible by calculating its determinant using np.linalg.det().
If the determinant is 0, the matrix is not invertible.
### Step 4: 
If the matrix is invertible, find the inverse using np.linalg.inv()

### Step 5:
Display the inverse matrix using the print() function.
### Step 6:
End the program.
## Program:
```
import numpy as np
A=np.array([[2, 1,1],[1,1,1],[1,-1,2]])
result=np.linalg.inv(A)
print(result)
```
## Output:
![alt text](Screenshot)
## Result:
Thus the inverse of given matrix is successfully solved using python program

