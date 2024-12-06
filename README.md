![Screenshot 2024-12-06 131522](https://github.com/user-attachments/assets/03ef932c-0058-4812-a4d9-e1a435207f00)# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: AGILAN J
RegisterNumber: 24900503
*/
  import numpy as np
  from scipy.linalg import lu
  a=np.array(eval(input()))
  p,l,u=lu(a)
  print(l)
  print(u)
```


(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: AGILAN J
RegisterNumber: 24900503
*/
  import numpy as np
  from scipy.linalg import lu,lu_solve,lu_factor
  a=np.array(eval(input()))
  b=np.array(eval(input()))
  lu,piv=lu_factor(a)
  x=lu_solve((lu,piv),b)
  print(x)
```


## Output:
![Screenshot 2024-12-06 131507](https://github.com/user-attachments/assets/a868a98c-56bb-4bc8-b225-908e2e6950ef)
 ![Screenshot 2024-12-06 131522](https://github.com/user-attachments/assets/4bdbb25b-2875-4920-979e-ed7fbf98bd62)





## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

