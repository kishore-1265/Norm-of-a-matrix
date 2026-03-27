# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
    1.Import the required module NumPy using import numpy as np to handle matrix operations.
    2.Read the matrix input from the user using eval(input()).
    3.Convert the given input into a NumPy array using np.array().
    4.Compute the 1-norm of the matrix using np.linalg.norm(mat, 1) and store the result.
    5.Compute the 2-norm of the matrix using np.linalg.norm(mat, 2) and store the result.
    6.Compute the infinity norm using np.linalg.norm(mat, np.inf) and store the result.
    7.Format each result to 2 decimal places using "{:.2f}".format().
    8.Display all three norm values using print().
 
## Program:
```Python
# Register No: 212225040192
# Developed By: Kishore R

# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
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
<br>
<br>
<br>
<img width="1348" height="238" alt="image" src="https://github.com/user-attachments/assets/97c54299-0617-4a57-834f-2e9260918994" />

### 2-Norm of a Matrix
<br>
<br>
<br>
<img width="1309" height="251" alt="image" src="https://github.com/user-attachments/assets/75db2570-0ccc-49d5-9bfa-c4b2a7449f49" />

### Infinity Norm of a Matrix
<br>
<br>
<br>
<img width="1337" height="293" alt="image" src="https://github.com/user-attachments/assets/1ae65cbd-5168-4aa1-8beb-3358ae1f76ad" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
