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
```
Register No:NIRANJAN S
Developed By:212224040221
```
# 1-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```

## Output:
### 1-Norm of a Matrix

![image](https://github.com/user-attachments/assets/b341b34a-d2e0-44ad-9736-7d6e4f1b0388)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/68d31a71-95e7-4969-bb69-65f0acec1f82)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/9dab846d-de35-482a-b4eb-d39bbaeb1c12)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
