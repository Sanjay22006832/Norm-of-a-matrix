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

# 1-Norm of a Matrix
```
Program to find 1-norm of a matrix.
Developed by: M Sanjay
RegisterNumber: 212222240090
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix

```
Program to find 2-norm of a matrix.
Developed by: M Sanjay
RegisterNumber: 212222240090
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```


# Infinity Norm of a Matrix
```
Program to find infinity norm of a matrix
Developed by: M Sanjay
RegisterNumber: 212222240090
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:

## 1-Norm of a Matrix
![Screenshot 2023-06-12 210601](https://github.com/Sanjay22006832/Norm-of-a-matrix/assets/119830477/3db0d056-9451-49e3-bd21-e9979071d873)


### 2-Norm of a Matrix
![Screenshot 2023-06-12 210640](https://github.com/Sanjay22006832/Norm-of-a-matrix/assets/119830477/eca89a4d-e2c7-4db2-b4a1-8996a6abdfbe)


### Infinity Norm of a Matrix
![Screenshot 2023-06-12 210652](https://github.com/Sanjay22006832/Norm-of-a-matrix/assets/119830477/cfdabdcf-43ae-4a1c-b42b-492eb012cb88)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
