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
# Register No:23004742
# Developed By:L.yagnesh kumar reddy
# 1-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: L.yagnesh kumar reddy
#RegisterNumber:23004742 

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: L.yagnesh kumar reddy
#RegisterNumber:23004742 

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
#Program to find 2-norm of a matrix.
#Developed by: L.yagnesh kumar reddy
#RegisterNumber:23004742 

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-24 211735](https://github.com/23004742/Norm-of-a-matrix/assets/150319318/0c8535f8-a8e9-4df0-acba-4cafb9ece253)


### 2-Norm of a Matrix
![Screenshot 2023-12-24 211959](https://github.com/23004742/Norm-of-a-matrix/assets/150319318/29403a21-1956-48f4-a55b-006df4bebf5b)


### Infinity Norm of a Matrix
![Screenshot 2023-12-24 212019](https://github.com/23004742/Norm-of-a-matrix/assets/150319318/c65053aa-9204-4878-ad81-01affb0577c8)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
