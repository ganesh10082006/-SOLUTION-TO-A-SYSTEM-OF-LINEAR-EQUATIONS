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
~~~
import numpy as np

coefficients = np.array([[5, -3, -10], [2, 2, -3], [-3, -1, 5]])
constants = np.array([-9, 4, -1])
solution = np.linalg.solve(coefficients, constants)
rounded_solution=np.around(solution)
print(f"{rounded_solution}")
~~~
## Output:
![Screenshot 2024-04-03 101758](https://github.com/ganesh10082006/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/151981672/249512bb-eeed-4a90-a081-a755fdb74b4a)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

