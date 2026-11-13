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
'''Program to find the solution for 1-Norm of a matrix
Developed by : Sre Vishnu Priyar L N
Register Number: 26009605
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
a=np.linalg.norm(mat,1)
norm_of_mat="{:.2f}".format(a)
print(norm_of_mat)
```
# 2-Norm of a Matrix
```python
'''
Program to find 2-norm of a matrix.
Developed by: Sre Vishnu Priyar L N
RegisterNumber: 26009605
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_mat="{:.2f}".format(ans)
print(norm_of_mat)
```
# Infinity Norm of a Matrix
```python
'''
Program to find the infinity of a matrix
Developed by : Sre Vishnu Priyar L N
Register Number : 26009605
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c061b60a-31e9-4710-ad2b-fafe1fac5978" />
### 2-Norm of a Matrix
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5c076f6b-540f-483f-b461-5f20e2022725" />
### Infinity Norm of a Matrix
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/206c8d12-69a0-43c7-bc3c-16596aeaffb0" />
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
