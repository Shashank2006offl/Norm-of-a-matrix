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
Program to find 1 norm of matrix
Devoloped by:Shashank R
Register number:212223220205
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```


# 2-Norm of a Matrix

```
Program to find 1 norm of matrix
Devoloped by:Shashank R
Register number:212223220205

import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

# Infinity Norm of a Matrix
```
'''
Program to find 1 norm of matrix
Devoloped by:Shashank R
Register number:212223220205
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Shashank2006offl/Norm-of-a-matrix/assets/147140026/79cc5aea-bf98-4dad-bbc3-3aec19219384)


### 2-Norm of a Matrix
![image](https://github.com/Shashank2006offl/Norm-of-a-matrix/assets/147140026/26a036f8-6a9d-4349-bba0-df134d4e8adf)


### Infinity Norm of a Matrix
![image](https://github.com/Shashank2006offl/Norm-of-a-matrix/assets/147140026/6b64a1b4-96c8-4b7b-86d8-460b2f08d0b2)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
