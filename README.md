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
``` python
#Program to find the solution for the given linear equations.
#Developed by: pavithran
#RegisterNumber:23001643
import numpy as np
a=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b=[-9,4,-1]
c=np.array(a)
d=np.array(b)
print(np.linalg.solve(c,d))
```

## Output:
![output](/linear%20equation.pnggit config)
## Result: 
Thus the solutions for the linear equations are successfully solved using python program

