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
# Register No:212222230008
# Developed By:AdhithyaRam D
# 1-Norm of a Matrix

import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)



# Infinity Norm of a Matrix
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)

```
## Output:
### 1-Norm of a Matrix
<br>![Screenshot 2023-06-03 150303](https://github.com/Adhithyaram29D/Norm-of-a-matrix/assets/119393540/dfbfd08a-125b-4662-9139-19f70b5559da)

<br>
<br>

### 2-Norm of a Matrix
<br>![Screenshot 2023-06-03 150424](https://github.com/Adhithyaram29D/Norm-of-a-matrix/assets/119393540/ace6329a-f403-4d6a-a4a9-f9bc9eea3749)

<br>
<br>

### Infinity Norm of a Matrix
<br>![Screenshot 2023-06-03 150507](https://github.com/Adhithyaram29D/Norm-of-a-matrix/assets/119393540/8a644b8b-9f04-4a71-8627-b91fa51c5803)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
