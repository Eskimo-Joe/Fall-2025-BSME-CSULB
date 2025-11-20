---
due: 2025-11-20
tags:
  - MAE305
submitted: F
src:
---
# Assignment - ODE
#### by Joseph Ramirez
#### November 20, 2025


### 1. Euler Method
$$\frac{dy}{dx}=e^{x}-y;\quad y(0)=1$$
$$y'+y=e^{x}\to y= \frac{\int e^{2x} \, dx }{e^{x}}=\frac{\frac{1}{2} e^{2x}+C}{e^{x}}=\frac{e^{x}}{2}+ Ce^{-x}$$$$y(0)=\frac{e^{0}}{2}+Ce^{-0}=-1\to C=-\frac{3}{2}$$
Exact equation: $y=\frac{1}{2}(e^{x}-3e^{-x})$

![[Pasted image 20251119231303.png]]


### 2. Huen's Method

![[Pasted image 20251119231323.png]]


### 3. fourth order Runge-Kutta Method

![[Pasted image 20251119231414.png]]

`<div style="page-break-after: always;"></div>
## 4. Adams Method

![[Pasted image 20251119231542.png]]


### 5. Adams-Moulton Method

![[Pasted image 20251119231605.png]]


`<div style="page-break-after: always;"></div>
## Conclusion
The most accurate method was Huen's method, as it made a necessary correction to Euler's method, which also performed excellently. The fourth-order Runge-Kutta method was also great, but it begins to overcomplicate the nature of the ODE. Adam's method was the worst, as the integral completely negates the -y term in the ODE, leading to large errors. The Adams-Moulton method was a great addition on top of the Runge-Kutta method. Adam's-Moulton does not make the mistake of changing the ODE by integrating, while enhancing the accuracy of a previous method. 

