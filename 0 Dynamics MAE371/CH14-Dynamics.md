---
date: 2025-10-02
tags:
  - MAE371
---

## linear momentum of the system of particles
$$\frac{d}{dt}(\vec{L}=\sum m_{i}\vec{v}_{i})$$
$$\dot{\vec{L}}=\sum \dot{m}_{i}\dot{\vec{v}}_{i}=\sum \dot{m}\vec{a_{i}}$$


## angular momentum

$o$ - any fixed point
$$\vec{H_{o}}=\sum  \vec{r}_{i}\times m \vec{v_{i}}$$
for v that is $\perp$ to r
$$\frac{d}{dt}\vec{H_{o}}=\dot{\vec{H_{o}}}=\sum \dot{\vec{r_{i}}}\times m_{i}\vec{v}_{i}+\sum \vec{r}_{i}\times m_{i}\dot{\vec{v}}_{i}$$
$$=\sum \vec{v}_{i}\times m_{i}\vec{v}_{i}+\sum \vec{r}_{i}\times m_{i}\dot{\vec{v}}_{i}$$
$$=\sum m_{i}(\vec{v}_{i}\vec{\times}v_{i})+\sum \vec{r}_{i}\times m_{i}\dot{\vec{v}}_{i}$$
$$\dot{\vec{H}}_{o} =0+\sum \vec{r}_{i}\times m_{i}\dot{\vec{v}}_{i}$$
$$=\sum \vec{r}_{i}\times m_{i}\vec{a}_{i}$$
$$M=F\times r$$

## Mass Center

$$\vec{r}_{G}=\frac{\sum m_{i}\vec{r}_{i}}{\sum m_{i}}$$
$$m \vec{r}_{G}=\sum m_{i} \vec{ r}_{i}$$
$$\frac{d}{dt}(m \vec{r}_{G})=m \vec{v}_{G}=\sum m_{i} \vec{v}_{i}$$
$$\frac{d}{dt}(m \vec{v}_{G})=m \vec{a}_{G}=\sum m_{i} \vec{a}_{i}$$

## Angular momentum about CG

$$\vec{H}_{G}=\sum \vec{r}_{i}'\times m_{i}\vec{ v}_{i}'$$
$$\vec{r}=\vec{r}_{G}+\vec{r}'$$
$$\dot{\vec{r}}=\dot{\vec{r}}_{G}+\dot{\vec{r}}'$$
...


$$\dot{\vec{H}}_{G}'=\frac{d}{dt}(\vec{H}_{G}')=\frac{d}{dt}\left( \sum \vec{r}_{i}' \times m_{i} \vec{v}_{i}' \right)$$
$$=\sum \vec{r}_{i}'\times m_{i}\vec{a}_{i}'$$
$$\dot{\vec{H}}_{G}'=\sum \vec{r}_{i}' \vec{\times}F$$
$$\vec{a}_{i}'=\vec{a}_{i}-\vec{a}_{G}$$

## 5
$$\vec{H}_{G}=\sum \vec{r}_{i}\times m_{i} \vec{ v}_{i}'$$


## 6
$$\dot{\vec{L}}= \frac{d \vec{L}}{dt}=\vec{F}=0$$
$$\vec{L}=\text{constant}$$
conservation of linear momentum

$$\dot{\vec{H}}=\frac{d \vec{H}}{dt}=M=0$$
$$\vec{H}=\text{constant}$$
conservation of angular momentum


## 10-09


system of particles in 3D
given masses, positions, and velocities

$$m_{a}=1kg;\quad m_{B}=2kg;\quad m_{C}=3kg$$
$$\vec{r}_{A}=\bra{0,3,1};\quad \vec{r_{B}}=\bra{3,0,2.5} ;\quad \vec{r}_{c}=\bra{4,2,1}  $$
$$\vec{v}_{A}=(3,-2,4);\quad \vec{v_{B}}=4,3,0;\quad \vec{v}_{C}=2,5,-3$$
$$\vec{H}_{o}=\sum \vec{r}_{i}\times m_{i}\vec{v_{i}}$$
$$\vec{H}_{o}=(1)\begin{bmatrix}
i & j & k \\
0 & 3 & 2 \\
3 & -2 & 4
\end{bmatrix}+(2)\begin{bmatrix}
i & j & k \\
3 & 0 & 2.5 \\
4 & 3 & 0
\end{bmatrix}+(3)\begin{bmatrix}
4 & 2 & 1 \\
2 & 5 & -3
\end{bmatrix}$$
$$H_{i}=i\begin{bmatrix}
3 & 1 \\
-2 & 4
\end{bmatrix}-j\begin{bmatrix}
0 & 1  \\
3 & 4
\end{bmatrix}+k\begin{bmatrix}
0 & 3 \\
3 & -2
\end{bmatrix}$$
$$H_{i}=(14,3,-9)$$
$$\vec{H}_{o}=(-34,65,57)$$

find the mass center 
$$\vec{r}_{G}=\frac{\sum m \vec{r}}{\sum m}=\frac{(0,3,1)+2(3,0,2.5)+3(4,2,1)}{1+2+3}=(3,1.5,1.5)$$

$$\langle \rangle $$
$$r_{a}'=r_{a}-r_{G}$$
$$\vec{H}_{G}=\sum   \vec{r}_{i}'\times m \vec{v}_{i}$$




## 10-14

two objects collide and the second explode into two pieces
$V_{A}=16 \frac{ft}{s}$ and $V_{B}=0 \frac{ft}{s}$
A and B have mass m and C and D have mass m/2
C moves at 30 degrees above horizontal and moves 6.3' in the x direction after t=0.7s and D moves 6.3' in the x direction in 0.9s . Determine the direction and distance of D

$$m \vec{v}_{A}+m \vec{v}_{B}=m \vec{v}_{A}+\frac{m}{2} \vec{v}_{C}+ \frac{m}{2} \vec{v}_{D}$$
horizontal component

$$16m=m \vec{v}_{A}'+ \frac{m}{2}\left( \frac{6.3}{0.7} \frac{ft}{s} \right)+\frac{m}{2} \vec{v}_{D}$$
$$v_{c}= \frac{6.3}{0.7\cdot \cos(30)}=10.39 \frac{ft}{s}$$

$$\vec{v}_{dx}=7 \frac{ft}{s}$$
$$v_{cx}=9 \frac{ft}{s};\quad v_{cy}=5.19 \frac{ft}{s}$$
sum of momentum in the y direction


