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
# Register No: 22007928
# Developed By: Kavinraja D
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
![n1](https://user-images.githubusercontent.com/119875375/214384785-047264e7-6f2d-40f8-ace3-b34c5c982608.png)

### 2-Norm of a Matrix

![Screenshot 2025-05-13 231521](https://github.com/user-attachments/assets/5f3c49d7-f505-460f-9a45-d8c0946a91ea)


### Infinity Norm of a Matrix
![n3](https://user-images.githubusercontent.com/119875375/214384921-521f3eb2-f4ea-463a-b822-1e9c8b86a8e0.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
