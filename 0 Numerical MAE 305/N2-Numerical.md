---
date: 2025-08-28
tags:
  - MAE305
---

## graphical solutions
$$v(t)=\sqrt{ \frac{gm}{C_{d}} }\tanh\left( \sqrt{\frac{gC_{d}}{m}  }t \right)$$
![[Pasted image 20250902152231.png]]

![[Pasted image 20250902152416.png]]


## fixed point interaction

given $f(x)=0$
rewrite $x=g(x)$
iterate using $x_{new}=g(x_{old})$
Error: $$E_{i+1}=E_{1}g'(x_{i})$$
ex: $f(x)=x-x^{1/3}-2=0$
$$x=x^{1/3}+2$$
start with a random number and calc
$$3=3^{1/3}+2=3.442249$$
$$3.442249=3.442249^{1/3}+2=3.5098974$$
converges to 3.521380

$$Error=\frac{\text{Present}-\text{Previous}}{\text{Present}}$$

5 correct sig figs




