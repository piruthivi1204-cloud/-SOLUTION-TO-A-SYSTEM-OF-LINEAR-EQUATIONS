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
#Developed by: V Jagan Kumar
#RegisterNumber:212225100018

import numpy as np
A = np.array([
    [1,-3],
    [3,1],
])

B = np.array([0,10])


solution = np.linalg.solve(A,B)

print(solution)
```

## Output:
![WhatsApp Image 2026-01-30 at 6 22 30 PM](https://github.com/user-attachments/assets/a9dd8700-779d-406d-9452-640f1a8f1542)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

