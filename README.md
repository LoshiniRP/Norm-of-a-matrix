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
# Register No: 25002119
# Developed By: R P Loshini
# 1-Norm of a Matrix
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A,1)
print("{:.2f}".format(norm))
# 2-Norm of a Matrix
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A,2)
print("{:.2f}".format(norm))
# Infinity Norm of a Matrix
import numpy as np
A = np.array(eval(input()))
norm = np.linalg.norm(A,np.inf)
print("{:.2f}".format(norm))
```

## Output:
### 1-Norm of a Matrix
<img width="1148" height="222" alt="Screenshot 2025-11-29 180954" src="https://github.com/user-attachments/assets/19d7eb66-9252-4695-bc81-476e377bd50d" />
<br>
<br>
<br>

### 2-Norm of a Matrix
<img width="1151" height="271" alt="Screenshot 2025-11-29 181130" src="https://github.com/user-attachments/assets/323b825d-52c6-4373-a0fb-582b5b8fcac6" />
<br>
<br>
<br>

### Infinity Norm of a Matrix
<img width="1152" height="228" alt="Screenshot 2025-11-29 181221" src="https://github.com/user-attachments/assets/fcbddba2-5f24-41f0-a876-c797af990e9a" />
<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
