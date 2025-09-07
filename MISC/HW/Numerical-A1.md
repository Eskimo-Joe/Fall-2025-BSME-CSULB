---
due: 2025-09-09
tags:
  - MAE305
submitted: F
src: https://docs.google.com/document/d/1VK-heeZpnBVOmcLtaXf93jDyn43a_RFuCFJZHPFihPo/edit?tab=t.0
---
Assignment 1 by Joseph Ramirez
## 1.
$$e^x-x^2=0$$
has a root in the interval [−1, 0]. Use bisection method to find it. How many iterations are needed to get results that agree to five significant digits? If you use hand calculator, stop after 3 iterations.

| a              | b               | m               | f(m)       |
| -------------- | --------------- | --------------- | ---------- |
| -1             | 0               | -.5             | 0.35653    |
| -1             | -.5             | -.75            | -0.09013   |
| -.75           | -.5             | -.625           | 0.14463    |
| -.75           | -.625           | -.6875          | 0.03018    |
| -.75           | -.6875          | -.71875         | -0.02924   |
| -.71875        | -.6875          | -.703125        | 6.51131E-4 |
| -.71875        | -.703125        | -.7109375       | -0.01425   |
| -.7109375      | -.703125        | -0.70703125     | -0.00678   |
| -0.70703125    | -.703125        | -0.705090625    | -0.00309   |
| -0.705090625   | -.703125        | -0.7041078125   | -0.00122   |
| -0.7041078125  | -.703125        | -0.70361640625  | -2.834E-4  |
| -0.70361640625 | -.703125        | -0.703370703125 | 1.839E-4   |
| -0.70361640625 | -0.703370703125 | -0.70349        | -4.97E-5   |
| -0.70349       | -0.703370703125 | -0.70343        | 6.71E-5    |
| -0.70349       | -0.70343        | -0.70346        | 8.71E-6    |
Ans = -.70346

## 2. 
Use MATLAB function fzero to solve the above equation.
Ans = -.70346

## 3.
Find the roots of:  x5 + 0.9x3 – 3.6x2 – 11.84 = 0. Use MATLAB function roots
Ans = 1.78651

## 4. 
$e^{x}-2x^2=0$ has a root near $x=2.6$
Find it using Newton’s method
$$f'(x)=e^{x}-4x$$

| x       | f(x)     | f'(x)   | $x-\frac{f(x)}{f'(x)}$ |
| ------- | -------- | ------- | ---------------------- |
| 2.6     | -0.05626 | 3.06374 | 2.618363830182458      |
| 2.61836 | 0.00161  | 3.23981 | 2.617866983581984      |
| 2.61787 | 1.2E-6   | 3.235   | 2.617866613067019      |
| 2.61787 | 6.7E-13  | 3.235   | 2.617866613066812      |
ans = 2.61778

## 5.
$x^2+\exp(x)-5=0$ has root near  $x=1$. Find it using Secant method. Select two initial guesses.

```desmos-graph
left=0; right=5;
top=10; bottom=-10;
---
y=x^2+e^x-5
```

| $x_{k-1}$   | $x_{k}$     | $f(x_{k})$          | $f(x_{k-1})$    | $x_{k-1}-x_{k}$  | $x_{k}-\frac{f(x_{k})(x_{k-1}-x_{k})}{f(x_{k-1})-f(x_{k})}$ |
| ----------- | ----------- | ------------------- | --------------- | ---------------- | ----------------------------------------------------------- |
| 0           | 1           | -1.281718172        | -4              | -1               | 1.471517765                                                 |
| 1           | 1.471517765 | 1.5212058           | -1.281718172    | -0.4715177647    | 1.215615155                                                 |
| 1.471517765 | 1.215615155 | -0.1499118384       | 1.5212058       | 0.2559026095     | 1.238571547                                                 |
| 1.215615155 | 1.238571547 | -0.01525971796      | -0.1499118384   | -0.02295639143   | 1.241173125                                                 |
| 1.238571547 | 1.241173125 | 0.0001804369294     | -0.01525971796  | -0.002601578478  | 1.241142723                                                 |
| 1.241173125 | 1.241142723 | -0.0000002132738031 | 0.0001804369294 | 0.00003040259864 | 1.241142758                                                 |
ans = 1.24114

## 6
**1. Solve    ex – 2x2 = 0 using the fixed-point method.  Find the root near x = 2.6 correct to 5 significant digits.
    

functions can be rearranged in several ways to give x = g(x) with which to begin the fixed-point method. For
$f(x)=e^{x}-2x^2$, one argument is $x=\pm \sqrt{ \frac{e^{x}}{2} }$

a) There is a root near 2.6. Show that we do not converge to this root even though values near to the root are used to start the iterations e.g. 2.5 or 2.7




```desmos-graph
left=0; right=5;
top=5; bottom=-5;
---
y=e^x-2*x^2
```



