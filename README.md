# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix.
## Program:
```
# Register No:24002708
# Developed By:Priya Varshini P
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)
```
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix with two decimal point.

## Program:
```
# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
print(round(result,2))
```
## Algorithm:
1. Get the input matrix using np.array()   
2. Find the infinity norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix.

## Program:
```
# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)
```
## Output:
### 1-Norm of a Matrix
<br>![exp 7 1 maths](exp%207.1.maths.png)
<br>
<br>
### 2-Norm of a Matrix
<br>![exp 7 2 maths](exp%207.2.maths.png)
<br>
<br>
### Infinity Norm of a Matrix
<br>![exp 7 3 maths](exp%207.3.maths.png)
<br>
<br>
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
