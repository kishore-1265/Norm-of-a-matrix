# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## 1-norm:
    1.Start the program.
    2.Import the required module NumPy using import numpy as np to perform matrix operations.
    3.Read the matrix input from the user using eval(input()).
    4.Convert the input into a NumPy array using np.array().
    5.Use np.linalg.norm(mat, 1) to compute the 1-norm (maximum column sum).
    6.Format the result to 2 decimal places using "{:.2f}".format().
    7.Display the final result using print().
    8.End the program.
## 2-norm:
    1.Start the program.
    2.Import the required module NumPy using import numpy as np to perform matrix operations.
    3.Read the matrix input from the user using eval(input()).
    4.Convert the input into a NumPy array using np.array().
    5.Apply np.linalg.norm(mat, 2) to calculate the 2-norm (largest singular value).
    6.Format the result to 2 decimal places using "{:.2f}".format().
    7.Display the final result using print().
    8.End the program.
## infinity-norm:
    1.Start the program.
    2.Import the required module NumPy using import numpy as np to perform matrix operations.
    3.Read the matrix input from the user using eval(input()).
    4.Convert the input into a NumPy array using np.array().
    5.Use np.linalg.norm(mat, np.inf) to compute the infinity norm (maximum row sum).m:
    6.Format the result to 2 decimal places using "{:.2f}".format().
    7.Display the final result using print().
    8.End the program.
## Progra

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
