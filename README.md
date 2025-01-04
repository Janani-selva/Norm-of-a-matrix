# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
```
1. Get the input matrix using np.array()   
2. Find the 1-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```

```  
1. Get the input matrix using np.array() 
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```

```   
1. Get the input matrix using np.array()   
2. Find the infinity-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
```
   
## Program:
```Python
# Register No: 24901127
# Developed By: janani s
# 1-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,1)
print(result)

# 2-Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,2)
norm_matrix="{:.2f}".format(result)
print(norm_matrix)

# Infinity Norm of a Matrix
import numpy as np
arr=np.array(eval(input()))
result=np.linalg.norm(arr,np.inf)
print(result)
```
## Output:
### 1-Norm of a Matrix
![WhatsApp Image 2024-12-27 at 07 37 11_689a3ab6](https://github.com/user-attachments/assets/16956cd1-2f82-4ed6-9a1f-ead5a0b27480)

### 2-Norm of a Matrix
![WhatsApp Image 2024-12-27 at 07 37 30_1f8df7cd](https://github.com/user-attachments/assets/f358f4dd-92d5-431b-8468-7d51ee824686)

### Infinity Norm of a Matrix
![WhatsApp Image 2024-12-27 at 07 37 52_85e49217](https://github.com/user-attachments/assets/f46da441-e5c6-4f71-9991-97a385897711)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
