# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Import numpy module
2. Get the input matrix using np.array()
3. Find the norm of the matrix using np.linalg.norm()
```
       1. np.linalg.norm(a,1) for 1-Norm
       2. np.linalg.norm(a,2) for 2-Norm
       3. np.linalg.norm(a,np.inf) for Infinity-Norm
```
4. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 212222230028
# Developed By: DEEPIKA.S
```
# 1-Norm of a Matrix
```

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)
```


# 2-Norm of a Matrix
```

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)
```

# Infinity Norm of a Matrix
```

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)
```

## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/119393935/236673210-aaa8a3e3-57b3-4092-8741-f99530f5b15f.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/119393935/236673241-df9aa9c6-df45-4ec9-b2aa-a2e2049f73e9.png)


### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/119393935/236673261-40bf642f-d20a-41d7-aa47-6f42b7f67007.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
