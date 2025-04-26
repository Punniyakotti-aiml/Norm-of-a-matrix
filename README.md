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
# Register No:212224240122
# Developed By:Punniyakotti.M
# 1-Norm of a Matrix
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 3-Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))




```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot (41)](https://github.com/user-attachments/assets/09015a44-6204-4c30-87d1-e2d651ddd0e1)
### 2-Norm of a Matrix
<br>![Screenshot (42)](https://github.com/user-attachments/assets/205f2608-a03e-4b1d-b57c-cc2b540f87ce)
### 3-Infinity Norm of a Matrix
<br>![Screenshot (43)](https://github.com/user-attachments/assets/d8aa01ff-0216-4304-8ae0-e8fd48831ac5)

 
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
