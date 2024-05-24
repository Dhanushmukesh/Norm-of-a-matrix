# Norm of a matrix
DATE:
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program:
```
# Register No:Dhanush.G
# Developed By:2305002006
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
# 2-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat, 2)
Norm_of_matrix = "{:.2f}". format(ans)
print(Norm_of_matrix)
# Infinity Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}". format(ans)
print(Norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-24 111841](https://github.com/Dhanushmukesh/Norm-of-a-matrix/assets/155508176/1e492540-aca7-475d-aa17-26ef2914534d)
### 2-Norm of a Matrix
![Screenshot 2024-05-24 111924](https://github.com/Dhanushmukesh/Norm-of-a-matrix/assets/155508176/9de7ec5a-8f97-4a55-8f8a-e75318540222)
### Infinity Norm of a Matrix
![Screenshot 2024-05-24 112019](https://github.com/Dhanushmukesh/Norm-of-a-matrix/assets/155508176/51d1f967-cf2a-48f0-ae9f-bb2d9d32b7c8)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
