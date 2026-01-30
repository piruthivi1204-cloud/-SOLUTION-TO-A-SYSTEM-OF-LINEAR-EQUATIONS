# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:

```python
#Program to find the solution for the given linear equations.
#Developed by: Piruthiviraj G
#RegisterNumber:25016420
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
result=np.linalg.solve(a,b)
print(result)
```
## Output:
<img width="1209" height="866" alt="image" src="https://github.com/user-attachments/assets/86c16d37-7f6d-49c0-9126-575434928277" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

