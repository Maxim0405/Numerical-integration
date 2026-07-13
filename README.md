# Numerical-integration
Implementation of various numerical integration methods in Julia. The project aims to demonstrate and graphically visualise numerical integration techniques — from elementary (Newton–Cotes) to advanced adaptive methods. The code may be useful for academic purposes.
# Features
Implemented:
- Rectangle methods (left, right, midpoint)
- Trapezoidal rule
- Adaptive Simpson's method
- Adaptive Gauss–Kronrod (G15–K21)
- Graphical visualisation for all implemented methods
# Usage
```julia
f(x) = exp(-x^2)
Adaptive_Gauss_Kronrod(f, 0, 5, 1e-6)  # 0.8862269254514016
```
# Testing
To get familiar with the project, clone the repository and navigate to its folder. Run the script:
```bash
julia example.jl
```
# Visualisation
Graphical demonstration of how adaptive methods refine the grid depending on the function behaviour, as well as illustrations for Newton–Cotes methods.
Example usage:
```julia
using Plots
f(x) = sin(x^2)
Visual_Simp(f,0,pi/2,10^-6)
Visual_GK(f,0,pi/2,10^-6)
Trap_Visual(f,0,pi/2,10)
Central_Visual(f,0,pi/2,10)
```
# Visualisation examples

<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/cb011291-66a8-49ab-ad19-603a02b1643d" />

<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/e359da6b-5db2-4300-8b40-7ee4df411898" />


<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/7ee3e203-859d-4a8b-98f3-0c153bf0e3ca" />

<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/a7984235-f930-4a17-8636-e9871ca54dc1" />





# Structure
- NumericalIntegration - main code
- example.jl -  examples
- USAGE.MD - user documentation





