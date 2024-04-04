-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
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
 #Developed by: K DEEKSHITHA
 #RegisterNumber: 2305002005
 import numpy as np
 A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
 B=np.array([-9,4,-1])
 solution=np.linalg.solve(A,B)
 print ('The solution for the given matrix is',solution)
```

## Output:
![image](https://github.com/kilarideekshi/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/155507099/832d0b37-db0f-45b8-a24f-46f24728f826)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

