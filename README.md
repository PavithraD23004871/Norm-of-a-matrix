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
# Register No:23004871
# Developed By:pavitra
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: pavithra.D
RegisterNumber: 23004871
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))
# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-28 131359](https://github.com/PavithraD23004871/Norm-of-a-matrix/assets/138955967/6556811a-5fef-40d6-8c0b-ca25c2260a6b)


### 2-Norm of a Matrix

![Screenshot 2023-12-28 131421](https://github.com/PavithraD23004871/Norm-of-a-matrix/assets/138955967/9cad3e64-d57b-4dd2-99aa-246948316c7b)

### Infinity Norm of a Matrix

![Screenshot 2023-12-28 131434](https://github.com/PavithraD23004871/Norm-of-a-matrix/assets/138955967/55b25c23-0f2a-4fca-8a8a-a8639907b217)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
