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
# Register No:U KRITHIGA
# Developed By:23006499
# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
sol=np.linalg.norm(mat,1)
mat_norm="{:.2f}".format(sol)
print(mat_norm)


# 2-Norm of a Matrix

import numpy as np
arr=np.array(eval(input()))
res=np.linalg.norm(arr,2)
norm="{:.2f}".format(res)
print(norm)



# Infinity Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))
sol=np.linalg.norm(mat,np.inf)
mat_norm="{:.2f}".format(sol)
print(mat_norm)




```
## Output:
### 1-Norm of a Matrix

![Alt text](<NORM 1.png>)
<br>
<br>
<br>

### 2-Norm of a Matrix

![Alt text](<NORM 2.png>)
<br>
<br>
<br>

### Infinity Norm of a Matrix

![Alt text](<NORM 3.png>)
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
