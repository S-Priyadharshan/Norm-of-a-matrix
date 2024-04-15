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
# Register No: 212223240127
# Developed By: Priyadharshan S
# 1-Norm of a Matrix

import numpy as np
matrix=eval(input())
res=np.linalg.norm(matrix,1)
print("{:.2f}".format(res))


# 2-Norm of a Matrix

import numpy as np
matrix=eval(input())
res=np.linalg.norm(matrix,2)
print("{:.2f}".format(res))

# Infinity Norm of a Matrix


import numpy as np
matrix=eval(input())
res=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(res))

```
## Output:
### 1-Norm of a Matrix:

![image](https://github.com/S-Priyadharshan/Norm-of-a-matrix/assets/145854138/6e2083aa-4cc7-42e8-94be-4be0656877d2)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/S-Priyadharshan/Norm-of-a-matrix/assets/145854138/c5b0f77e-8008-46b6-bb60-b5dceedfb43e)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/S-Priyadharshan/Norm-of-a-matrix/assets/145854138/80962e42-0932-4f98-a6ba-be8b7c34de60)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
