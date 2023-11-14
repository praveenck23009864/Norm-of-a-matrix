# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 23009864
# Developed By: praveen ck
# 1-Norm of a Matrix

import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix

![Screenshot 2023-11-14 194728](https://github.com/praveenck23009864/Norm-of-a-matrix/assets/141472050/eb8ce06b-1581-4f52-9f4c-40214f03bd81)

### 2-Norm of a Matrix
![Screenshot 2023-11-14 194747](https://github.com/praveenck23009864/Norm-of-a-matrix/assets/141472050/071b4d12-7f9f-4065-abdd-ac0ac2cf7fce)


### 3-Infinity Norm of a Matrix
![Screenshot 2023-11-14 194817](https://github.com/praveenck23009864/Norm-of-a-matrix/assets/141472050/eadfa979-7e98-439f-814e-ecc395f66c35)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
