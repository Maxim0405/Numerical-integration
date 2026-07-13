# Documentation

## Newton–Cotes Methods

Implemented Newton–Cotes methods:

1. Right rectangle method – `Right_Rectangle(f, x_0, x_n, n)`
2. Left rectangle method – `Left_Rectangle(f, x_0, x_n, n)`
3. Midpoint rectangle method – `Central_Rectangle(f, x_0, x_n, n)`
4. Trapezoidal rule – `Trapezoids(f, x_0, x_n, n)`

To compute a definite integral, use any of the above commands:

1. `f` – integrand function
2. `x_0` – lower limit of integration
3. `x_n` – upper limit of integration
4. `n` – number of steps

Example:

```
g(x) = x^2
Right_Rectangle(g,0,5,10)
```

This code returns the numerical value of the integral over the specified interval.

Visualization functions for integration methods:

1. Right rectangle visualization – `Right_Visual(f, x_0, x_n, n)`
2. Left rectangle visualization – `Left_Visual(f, x_0, x_n, n)`
3. Midpoint rectangle visualization – `Central_Visual(f, x_0, x_n, n)`
4. Trapezoidal rule visualization – `Trap_Visual(f, x_0, x_n, n)`

Example:

```
g(x) = x^3
Trap_Visual(g,1,9,50)
```

This code returns a plot where the integrand is approximated by trapezoids over the specified interval.

## Adaptive Methods

1. Adaptive Simpson's method – `Adaptive_Simpson(f, x_0, x_n, epsilon)`
2. Adaptive Gauss–Kronrod method – `Adaptive_Gauss_Kronrod(f, x_0, x_n, epsilon)`

Function arguments are the same as for Newton–Cotes methods, except for the last parameter `epsilon` — the error tolerance you specify for numerical integration.

Example:

```
f(x) = sin(x^2)
Adaptive_Gauss_Kronrod(f,1,4,10^-6)
```

Visualization of adaptive methods:

1. Adaptive Simpson visualization – `Visual_Simp(f, x_0, x_n, epsilon)`
2. Adaptive Gauss–Kronrod visualization – `Visual_GK(f, x_0, x_n, epsilon)`

Example:

```
f(x) = exp(x)
Visual_GK(f,1,4,10^-6)
```

This function returns a graphical visualization of how the adaptive method refines the grid depending on the behaviour of the function over the given interval.

## Notes

1. For more details on Newton–Cotes methods, see:  
   https://en.wikipedia.org/wiki/Newton%E2%80%93Cotes_formulas
2. For more details on adaptive quadrature methods, see:  
   https://en.wikipedia.org/wiki/Adaptive_quadrature
