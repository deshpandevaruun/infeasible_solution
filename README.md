# infeasible_solution
Consider the optimization problem 
Minimize (x-1.5)^2 + (y+1)^2
subject to 
0<= x <= 3
-1 <= y <= 0
x - y >= 1
x + y <= 2 
(x, y) = (1.5, -1) is an optimal solution but according to the Gurobi package it is an infeasible solution, yet it lies in the feasible region, though it is not a corner point.
