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
# Register No: 212225040274
# Developed By: Nanthikashree T
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))


# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))


# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array(eval(input()))
norm=np.linalg.norm(matrix,ord=np.inf)
print(f"{norm:.2f}")


```
## Output:
### 1-Norm of a Matrix
<img width="818" height="792" alt="image" src="https://github.com/user-attachments/assets/ee8f971f-3245-4a6f-a200-55f84a2380fc" />


### 2-Norm of a Matrix
<img width="807" height="822" alt="image" src="https://github.com/user-attachments/assets/4c5c33b4-2f80-4701-96dd-fb29122f58df" />


### Infinity Norm of a Matrix
<img width="683" height="788" alt="image" src="https://github.com/user-attachments/assets/1b6c07c5-deb9-47bd-ad0c-fc882959b7c0" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
