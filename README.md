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
# Register No:212223230129
# Developed By:Murali Krishna S
# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/98362176-0065-4313-9671-488b7eb7f152)
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/1998a37f-ed06-43a7-931a-47092d9d2f14)


### 2-Norm of a Matrix
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/3e695910-9168-4017-b1d2-60d4cdbfd811)
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/e9483ba1-9914-4bfa-9554-0aa08165d108)
)


### Infinity Norm of a Matrix
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/678b30ae-0fd5-455e-926f-68b10233c010)
![image](https://github.com/Murali-Krishna0/Norm-of-a-matrix/assets/149054535/f730d917-22f2-46c6-912b-d56f3337bb83)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
