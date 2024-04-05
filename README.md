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

## Developed by : N.PRAVESH
## Register no : 212223230154

## Program:

```python
import numpy as py
mat = py.array([[1,3],[2,5]])
rhs = py.array([5,-3])
sol = py.linalg.solve(mat,rhs)
print(sol)
```

## Output:

![Screenshot 2024-04-05 133348](https://github.com/NPravesh2005/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/164477756/6409aae6-f7d8-40ec-aefe-c965f2a44d27)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

