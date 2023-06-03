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
# Register No: 212222240026
# Developed By: DIVAKAR R

# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
sum=np.linalg.norm(a,2)
print("{:.2f}".format(sum))



# Infinity Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
sum=np.linalg.norm(a,np.inf)
print("{:.2f}".format(sum))


```
## Output:
### 1-Norm of a Matrix



![Screenshot 2023-06-03 220701](https://github.com/divakar618/Norm-of-a-matrix/assets/121932143/dec7c43f-6147-441c-995e-d389e0267aaa)





### 2-Norm of a Matrix




![Screenshot 2023-06-03 220808](https://github.com/divakar618/Norm-of-a-matrix/assets/121932143/473bff78-bfc3-4120-90d3-3dadd7d6c8e5)





### Infinity Norm of a Matrix





![Screenshot 2023-06-03 220940](https://github.com/divakar618/Norm-of-a-matrix/assets/121932143/b07f1541-e7ee-4921-81df-dd99e0d2cafc)





## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
