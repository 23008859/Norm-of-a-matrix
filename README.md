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
# Register No:23008859
# Developed By:Roshini.S
# 1-Norm of a Matrix
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
# 2-Norm of a Matrix:
'''
Program to find 2-norm of a matrix.
Developed by: Roshini.S
RegisterNumber: 23008859
'''
import numpy as np
array1=([[1,2],[3,4]])
array2=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)

# Infinity Norm of a Matrix
import numpy as np
array=([[-1,3],[3,-4],[1,7]])
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/23008859/Norm-of-a-matrix/assets/139117979/a30ae969-efce-40b5-ad4d-81ce3b760b55)

<br>
<br>
<br>

### 2-Norm of a Matrix
![image](https://github.com/23008859/Norm-of-a-matrix/assets/139117979/776043ed-bd3f-4dac-ab1b-05315d2dbad7)

<br>
<br>
<br>

### Infinity Norm of a Matrix
![image](https://github.com/23008859/Norm-of-a-matrix/assets/139117979/86b1b8c1-369a-46d0-91ec-e18634bc4bc5)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
