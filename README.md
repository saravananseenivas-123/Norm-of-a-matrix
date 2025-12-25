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
```
# Register No:25005837
# Developed By: SARAVANAN S
```
```
# 1-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# Infinity Norm of a Matrix
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```


## Output:
### 1-Norm of a Matrix
<img width="608" height="630" alt="NORM 01" src="https://github.com/user-attachments/assets/72ccd7da-290f-4c52-bddd-10a05b241696" />

### 2-Norm of a Matrix
<img width="606" height="690" alt="NORM 2" src="https://github.com/user-attachments/assets/8c25f2ca-df80-4021-b66b-3f3ac9750085" />

### 3-Infinity Norm of a Matrix
<img width="606" height="639" alt="NORM 3" src="https://github.com/user-attachments/assets/8f717375-4847-4355-8d6a-88c2bd68f67c" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
