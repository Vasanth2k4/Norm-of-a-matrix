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
# Register No:23012935
# Developed By:VASANTHARAJ J
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))

# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))

# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Vasanth2k4/Norm-of-a-matrix/assets/147139769/11ae8efa-1546-4a3f-b628-d7cc6a948445)

### 2-Norm of a Matrix
![image](https://github.com/Vasanth2k4/Norm-of-a-matrix/assets/147139769/bb69bdc4-d91a-4342-ad55-4a0e10e32bbf)

### Infinity Norm of a Matrix
![image](https://github.com/Vasanth2k4/Norm-of-a-matrix/assets/147139769/531a9d2b-4f0c-4c58-81f2-23ea230d1d99)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
