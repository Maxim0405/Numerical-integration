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

<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/b9ba24d8-875a-41e0-bc7e-ac4a834a4014" />


<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/4bed6667-f985-4305-9237-bcd3de487b09" />



<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/7378f809-7760-4e63-9035-602b24dc8acc" />


<img width="584" height="389" alt="изображение" src="https://github.com/user-attachments/assets/270608f4-87ef-4fe9-8468-abac8d815dae" />






# Structure
- NumericalIntegration - main code
- example.jl -  examples
- USAGE.MD - user documentation





