# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# Algorithm-1
	1. Get the input matrix using np.array()   
    2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in one decimal places.

# Algorithm-2
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
# Algorithm-3
	1. Get the input matrix using np.array()   
    2. Find the norm_infinity of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in  decimal places.
	
## Program:
```Python
# Register No:NAVEENKUMAR M
# Developed By:212224230183


# 1-Norm of a Matrix
import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm1=np.linalg.norm(arr,1)
print("{:.2f}".format(norm1))



# 2-Norm of a Matrix
import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm2=np.linalg.norm(arr,2)
print("{:.2f}".format(norm2))



# Infinity Norm of a Matrix
import numpy as np
matrix = eval(input())
arr=np.array(matrix)
norm_infinity=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm_infinity))





```
## Output:
### 1-Norm of a Matrix
<img width="1154" height="845" alt="image" src="https://github.com/user-attachments/assets/a6325adc-65bd-42f2-95e9-5e69d83b3bb6" />


### 2-Norm of a Matrix
<img width="1147" height="917" alt="image" src="https://github.com/user-attachments/assets/a3a309a4-e5e6-4679-a20f-0df1e05e51cc" />


### Infinity Norm of a Matrix
<img width="1151" height="855" alt="image" src="https://github.com/user-attachments/assets/e2f47004-5755-4285-9013-60ce0a96ebef" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
