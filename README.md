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
<br>![exp 7 1 maths](https://github.com/user-attachments/assets/08a85603-7604-42bf-81b1-c13a181cee77)
<br>
<br>
### 2-Norm of a Matrix
<br>![exp 7 2 maths](https://github.com/user-attachments/assets/44bac963-49f9-4da6-952b-95ef0ae49ee7)
<br>
<br>
### Infinity Norm of a Matrix
<br>![exp 7 3 maths](https://github.com/user-attachments/assets/c6d6e9a9-7993-4918-a989-25f205a1786a)
<br>
<br>
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
