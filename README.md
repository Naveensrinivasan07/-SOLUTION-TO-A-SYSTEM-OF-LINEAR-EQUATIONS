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
```
#Program to find the solution for the given linear equations.
#Developed by: naveen
#RegisterNumber:212222240700
import numpy as np
a = np.array([[1,3],[2,5]])
b = np.array([5,-3])
x = np.linalg.solve(a,b)
print(x)
```
## Output:
![Screenshot 2023-06-06 201719](https://github.com/Naveensrinivasan07/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/119475891/1b71ac15-d454-4b44-8e82-d7bc9c6727b3)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

