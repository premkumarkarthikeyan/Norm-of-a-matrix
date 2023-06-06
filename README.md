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
Python
# 1-Norm of a Matrix
#name: prem kumar.k
#register number : 212222230111

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)



# 2-Norm of a Matrix
#Developed by:prem kumar k
#RegisterNumber: 212222230111


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
nor_of_matrix="{:.2f}".format(ans)
print(nor_of_matrix)
```

## Output:
### 1-Norm of a Matrix
<br>![7a maths prem](https://github.com/premkumarkarthikeyan/Norm-of-a-matrix/assets/119476243/4520eb94-0465-4785-b1fa-a079dbc0ccf1)

<br>

### 2-Norm of a Matrix
<br>![7b maths prem](https://github.com/premkumarkarthikeyan/Norm-of-a-matrix/assets/119476243/48e518e3-0447-45c1-bbec-41d97885fa52)

<br>
<br>

### Infinity Norm of a Matrix
<br>![7c maths prem](https://github.com/premkumarkarthikeyan/Norm-of-a-matrix/assets/119476243/920ba1cd-7011-47c6-bcf1-7b373706c858)

<br>
<br>

## Result:

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
