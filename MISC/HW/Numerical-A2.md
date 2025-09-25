---
due: 2025-09-25
tags:
  - MAE305
submitted: T
src:
---
Assignment 2 by Joseph Ramirez
## 1
Do these equations have a solution? Find the solution if it exists. Explain why when it does not.

![[Pasted image 20250918153416.png]]
a. 
$$A=\begin{bmatrix}
-2 & 3 & 1 \\
-3 & 1 & 1 \\
1 & 1 & -1
\end{bmatrix}$$
$$\det A=(-2)(1)(-1)+3+(-3)-1-(-3)(3)(-1)-(-2)$$
$$\det A=2+3-3-1-9+2=2-1-9+2=-6$$
since A is nonsingular, there is a unique solution for $Ax=b$
$$\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}=\begin{bmatrix}
-2 & 3 & 1 & 2 \\
-3 & 1 & 1 & 5 \\
1 & 1 & -1 & -5 \\
0 & 3 & 1 & 0
\end{bmatrix}$$
$$3y=-z$$
$$x+y-z=-5\to x+4y=-5\to x=-5-4y$$
$$-3(-5-4y)+y-3y=5\to 15+10y=5\to y=-1\to z=3$$
$$x-1-3=-5\to x=-1$$
$$\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}=\begin{bmatrix}
-1 \\
-1 \\
3
\end{bmatrix}$$

b. 
$$\begin{bmatrix}
0 & 1 & 1 & 1 \\
1 & 1 & 0 & -2 \\
1 & 0 & 1 & 0 \\
1 & 1 & 1 & 4
\end{bmatrix}$$
$$y=1-z;\quad x=-z;\quad y=1+x$$
$$x+y=-2\to x+1+x=-2\to 2x=-3\to x=-\frac{3}{2};\quad z=\frac{3}{2}$$
$$x+y+z=4\to y=4$$
$$x+y=-2\to y=-2+\frac{3}{2}\ne 4$$
There is no solution to this system of equations because there is not consistency between all four equations. 

c. 
$$\begin{bmatrix}
2 & -1 & 6 & 1 \\
1 & 0 & 2 & 0 \\
3 & 2 & 2 & 0
\end{bmatrix}$$
$$\det A=(-1)(2)(3)+2(6)-(-1)(2)-8=-6+12+2-8=0$$
$$x=-2z$$
$$-4z-y+6z=1\to -y=1-2z\to y=2z-1$$
$$3x+2y+2z=0\to -6z+4z-2+2z=0\to -2\ne 0$$
there is no solution as the three equations are not consistent. Since the matrix A is singular, there will be either infinite or zero solutions, therefore there is zero solutions.

`<div style="page-break-after: always;"></div>
## 2
Use Gaussian elimination with partial pivoting to solve the equations (given as augmented matrix):
![[Pasted image 20250918153458.png]]
Are any row interchanges needed?
Row 1 no interchange
$$m_{21}=-\frac{2}{3};\quad R_{2}=R_{2}-m_{21}R_{1}=\frac{11}{3}y-\frac{5}{3}z=-\frac{1}{3}$$
$$m_{31}=\frac{2}{3};\quad R_{3}=R_{3}-\frac{2}{3}R_{1}=0x-\frac{2}{3}y+\frac{23}{3}z=\frac{16}{3}$$
$$m_{32}=-\frac{2}{11};\quad R_{3}=R_{3}+\frac{2}{11}R_{2}=-\frac{2}{3}y+\frac{2}{11} \frac{11}{3}y+\frac{23}{3}z+\frac{2}{11}\frac{-5}{3}z=\frac{16}{3}+\frac{2}{11}\left( -\frac{1}{3} \right)$$
$$R_{3}=\frac{23}{3}z- \frac{10}{33}z=\frac{16}{3}-\frac{2}{33}$$
$$\begin{bmatrix}
3 & 1 & -4 & 7 \\
0 & \frac{11}{3} & -\frac{5}{3} & -\frac{1}{3} \\
0 & 0 & \frac{243}{33} & \frac{174}{33}
\end{bmatrix}$$
$$\frac{243}{33}z=\frac{174}{33}\to z=\frac{174}{243}=\frac{58}{81}$$
$$\frac{11}{3}y-\frac{5}{3}\left( \frac{58}{81} \right)=-\frac{1}{3}\to y=\frac{19}{81}$$
$$3x+\frac{19}{81}-4\left( \frac{58}{81} \right)=7$$
$$x=\frac{260}{81}$$
$$\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}=\begin{bmatrix}
\frac{260}{81} \\
\frac{19}{81} \\
\frac{58}{81}
\end{bmatrix}$$
no interchanges were needed

`<div style="page-break-after: always;"></div>
## 3
Solve the system of equations, starting with the initial vector of [0, 0, 0]. If necessary, rearrange the equations in order to get convergence. (If you are not using a program, show only 4 iterations).

![[Pasted image 20250918153550.png]]
a. Solve using the Jacobi method.  
$$x_{3}=\frac{5.11-1.26x_{1}-3.11x_{2}}{4.57}$$
$$x_{2}=\frac{-3.17+3.07x_{1}-2.11x_{3}}{5.48}$$
$$x_{1}=\frac{2.22+1.21x_{2}-3.22x_{3}}{4.63}$$
$$x_{1}=x_{2}=x_{3}=0$$
![[Pasted image 20250924234254.png|400]]

`<div style="page-break-after: always;"></div>

b. Solve using the Gauss-Seidel method

![[Pasted image 20250925000555.png|400]]

`<div style="page-break-after: always;"></div>
## 4
Use MATLAB (A \ B) to solve the system of equations given below. Change the coefficients $a_{11}$ to 6.00 instead of 6.03 and $a_{33}$ to 1.00 instead of 0.987; then re-solve the equations. How do the answers change? Is the system is ill-conditioned? Explain. State all the evidence that support your answer.
![[Pasted image 20250918153642.png]]
$$A\text{\\}B=\begin{bmatrix}
-93.85102 \\
-73.30678 \\
237.60072
\end{bmatrix}$$
$$\begin{bmatrix}
6.00 & 1.99 & 3.00 & 1.0 \\
4.16 & -1.23 & 1.27 & 1.5 \\
-4.81 & 9.34 & 1.00 & 1.25
\end{bmatrix}$$
$$A\text{\\}B=\begin{bmatrix}
-196.97584 \\
-154.49353 \\
496.76572
\end{bmatrix}$$
yes, system is ill-conditioned
