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
# Register No:25017565
# Developed By:SEKAR M
# 1-Norm of a Matrix
```py
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,1)
c=f"{b:.2f}"
print(c)
```
# 2-Norm of a Matrix
```py
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,2)
print(f"{b:.2f}")
```
# Infinity Norm of a Matrix
```py
import numpy as np
a=np.array(eval(input()))
b=np.linalg.norm(a,np.inf)
print(f"{b:.2f}")
```
## Output:
### 1-Norm of a Matrix
<img width="877" height="332" alt="image" src="https://github.com/user-attachments/assets/cfae8ffa-f14d-4a47-8825-8bbea0f63e73" />


### 2-Norm of a Matrix
<img width="871" height="373" alt="image" src="https://github.com/user-attachments/assets/da829593-e489-427b-b13d-11e259bc6e46" />


### Infinity Norm of a Matrix
<img width="866" height="329" alt="image" src="https://github.com/user-attachments/assets/d7cd97ca-8594-4cc7-bfdb-d51853171bb6" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
