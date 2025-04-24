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
# Register No:24900209
# Developed By: S Niranjan
# 1-Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,1)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)   

# 2-Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,2)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)

# Infinity Norm of a Matrix
	import numpy as np
	mat = np.array(eval(input()))
	ans = np.linalg.norm(mat,np.inf)
	Norm_of_matrix ="{:.2f}".format(ans)
	print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-08 180603](https://github.com/user-attachments/assets/cc89ad5a-74c1-4029-a37f-916674296c08)

### 2-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-08 180621](https://github.com/user-attachments/assets/fb0733ea-0545-47f7-8427-b5dd2be3e7fe)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2024-12-08 180632](https://github.com/user-attachments/assets/38a8ca6c-70b0-4562-899f-e1684407d705)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
