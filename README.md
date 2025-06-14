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
# Register No:212224230189
# Developed By:Nitheesh Kumar B
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![Screenshot 2025-04-23 105252](https://github.com/user-attachments/assets/99ecf644-4f07-4ac2-b5bc-f5d1981e5eb3)

<br>
<br>

### 2-Norm of a Matrix
![Screenshot 2025-04-23 101434](https://github.com/user-attachments/assets/a5a82b5d-191c-4ac5-a2f5-59673b79feb3)

<br>

### Infinity Norm of a Matrix

![image](https://github.com/user-attachments/assets/ecef2fe8-5fe3-425e-aeef-c8ebd2ddd93e)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
