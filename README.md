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

# Register No:212224040221
# Developed By: Niranjan S
# 1-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)   
```
# 2-Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix ="{:.2f}".format(ans)
print(Norm_of_matrix)
```





## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-08 180603](https://github.com/user-attachments/assets/5fe1cdc5-5f79-4e19-9fc6-e6cb4bc52b4f)


### 2-Norm of a Matrix
![Screenshot 2024-12-08 180621](https://github.com/user-attachments/assets/9f76e586-7a21-4ff0-9c8e-285b910fae96)


### Infinity Norm of a Matrix
![Screenshot 2024-12-08 180632](https://github.com/user-attachments/assets/b6bd8741-3353-49c2-958e-f72cd456f31c)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
