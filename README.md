# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
Step 1: Initialize matrices2.

Step 2: For each row i from 0 to n–1

Step 3: After all iterations 

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input())) 
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

```

## Output:
(i)
<img width="1214" height="468" alt="Screenshot 2025-12-23 183028" src="https://github.com/user-attachments/assets/ba0b704c-50ee-4655-8c94-9e04989fdd68" />
(ii)
<img width="1233" height="205" alt="Screenshot 2025-12-23 183127" src="https://github.com/user-attachments/assets/075407fa-0fb4-42f2-8d5d-227f459fcb8e" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

