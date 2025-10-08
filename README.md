# C-Linear-Approximator
This program implements "first-order taylor series linear approximations" for several mathematical functions (sin(x), cos(x), tan(x), log(x), exp(x), x^2).  
It computes the derivative numerically using the "central difference method" and includes necessary checks for domain and discontinuity handling.  

## Features
- Supports 'sin', 'cos', 'tan', 'log', 'exp' and x^2.  
- Handles both "Radians" and "Degrees" for trigonometric inputs.  
- "Central difference" method for derivative calculation.  
- Validation for logarithmic domain (x>0).  
- Discontinuity protection for tan(x) near "π/2 + nπ".  

## Formula
The linear approximation is calculated as:  
F(x) = F(a) + F'(a)*(x-a)  
Where F'(a) is estimated numerically.  

## Compilation and usage
Compile: gcc linear_approximator.c  
Run: .\a.exe  

