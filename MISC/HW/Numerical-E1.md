---
due: 2025-10-02
tags:
  - MAE305
submitted: T
src:
---

## sources of error
1. Truncation 
2. Round-off
	1. Addition and sub
	2. non-terminating numbers
3. Propagating (multiplying)
## error definition
True Error
$$E_{t}=\text{True Value} - \text{calculated value}$$
True percent relative error: 
$$\epsilon_{t}=\frac{True-calculated}{true}$$
Approximate percent relative error
$$\epsilon_{a}=\frac{Present-Previous}{Present}$$
Stopping Criteria: $\epsilon_{s}$
$$\epsilon_{a}<\epsilon_{s}$$
`<div style="page-break-after: always;"></div>
## taylor series
![[Pasted image 20250929100737.png|500]]
## fixed point interaction

given $f(x)=0$
rewrite $x=g(x)$
iterate using $x_{new}=g(x_{old})$
Error: $$E_{i+1}=E_{1}g'(x_{i})$$
$$Error=\frac{\text{Present}-\text{Previous}}{\text{Present}}$$
## bisection method
![[Pasted image 20250902153625.png|500]]
`<div style="page-break-after: always;"></div>
## Newton's Method
$$x_{k+1}=x_{k}+\frac{f(x_{k})}{f'(x_{k})}$$
## Secant Method
$$x_{k+1}=x_{k}-\frac{f(x_{k})(x_{k-1}-x_{k})}{f(x_{k-1})-f(x_{k})}$$
## Matrix Review
$$Ax=b$$
if $\det A=0$ then A ^ has either infinite or no solutions
(linearly dependent, singular)
if $\det A\ne 0$ then there is a unique solution to ^
(linearly independent, nonsingular)
`<div style="page-break-after: always;"></div>
## Naive Gauss
arrange the strongest coefficients in the diagonal (top left to bottom right). Use the following factor to get upper triangular
$$m_{21}=\frac{a_{21}}{a_{11}};\quad R_{2}=R_{2}-m_{21}R_{1}$$
![[Pasted image 20250929104058.png]]
`<div style="page-break-after: always;"></div>
## LU Decomposition
![[Pasted image 20250929110707.png]]
`<div style="page-break-after: always;"></div>
## Jacobi Iterative
![[Pasted image 20250929104716.png]]
## Gauss-Seidel
Jacobi but iterate each x every time
## Matrix Inverse
augment A with I and use gaussian to find inverse
Scaling Reduces Round-off errors
`<div style="page-break-after: always;"></div>
## Banded Matrix
![[Pasted image 20250929111822.png]]
the minimum rxr submatrix size inside A where one submatrix determinant is nonzero. Corresponds to number of lin. independent rows
`<div style="page-break-after: always;"></div>
## Matrix Norm
![[Pasted image 20250929112407.png|300]]
`<div style="page-break-after: always;"></div>
## Condition number
![[Pasted image 20250929112447.png|350]]
## Ill conditioned system
small changes in A or B produce large change in solution
likely ill conditioned if true: $abs(\det A)<<abs(a_{ij})$ or $k(A)\gg 1$
## Existence Model
![[Pasted image 20250929112627.png|400]]
`<div style="page-break-after: always;"></div>
## System of nonlinear equations
![[Pasted image 20250929112946.png]]


