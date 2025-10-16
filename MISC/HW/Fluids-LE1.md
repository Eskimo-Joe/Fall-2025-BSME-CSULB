---
due: 2025-10-16
tags:
  - CE336
submitted: T
src:
---

### Name
Joseph Ramirez
### Student ID
027867994

### 1
False


### 2
a) The theoretical velocity is calculated using bernoulli's equation, where static head converts into dynamic head: 
$h=\frac{V^2}{2g}\to V_{t}=\sqrt{ 2gh }$. The actual velocity is measured in the lab by measuring the displacement of the jet stream and usually differs from theoretical velocity. 

b) The actual velocity is calculated by measuring the vertical and horizontal displacement of the jet stream. Using kinematic equations, we know the vertical velocity starts at zero and accelerates constantly due to gravity while horizontal velocity doesn't change. The vertical displacement allows us to solve for the air time of the jet stream, and the horizontal displacement and time can solve for the exit velocity of the stream which is assumed to be horizontal. The coefficient of velocity is actual velocity divided by theoretical velocity ($C_{v}=\frac{V_{a}}{V_{t}}$) and can be used to solve for actual velocity from other theoretical velocities which correspond to different levels of head. 
### 3
False
`<div style="page-break-after: always;"></div>
### 4
a) the minor head loss is the head loss due the valve, which can disturb the fluid flow even while fully open. The major head loss comes from the friction of the fluid against the pipe walls. 
$$h_{minor}=K \frac{V^2}{2g}$$
$$h_{major}=\frac{fLV^2}{2Dg}$$
b) The head loss coefficient $K$ can be solved by measuring the head loss and flow rate across the valve or bend, and solving the equation for $K=\frac{2gh}{V^2}=\frac{2gh}{\left( \frac{Q}{A} \right)^2}$. Measure the head loss by using two open manometers, one before and one after the valve or bend. The head loss is the height of the upstream manometer minus the height of the second manometer in meters and plug this value into $h$. The flow rate can be found by filling a container of known volume on a timer and dividing volume over time. Then plug this flow rate into Q. Gravity is a known constant and measure the pipe diameter and solve for area, and K can be solved. 


### 5 
$H$ is referred to as the "height above the notch" and measures the height of the water surface above the lowest point of the weir. 

`<div style="page-break-after: always;"></div>
### Problem 1
$$D_{1}=10cm=.1m;\quad A_{1}=\frac{\pi}{4}D_{1}^2=.00785m^2$$
$$D_{2}=5cm=.05m;\quad A_{2}=\frac{\pi}{4}D_{2}^2=.00196m^2$$
$$h_{1}-h_{2}=50cm=.5m$$
$$T=20^{\circ}C=293.15K$$
$$A_{1}V_{1}=A_{2}V_{2}\to V_{2}=\frac{A_{1}}{A_{2}}V_{1}=(\frac{D_{1}}{D_{2}})^2V_{1}=4V_{1}$$
$$z_{1}+\frac{P_{1}}{\gamma}+\frac{V_{1}^2}{2g}=z_{2}+\frac{P_{2}}{2g}+\frac{V_{2}^2}{2g}$$
$$z_{1}=z_{2};\quad \frac{P_{1}}{\gamma}=h_{1};\quad \frac{P_{2}}{\gamma}=h_{2}$$
$$h_{1}-h_{2}=\frac{V_{2}^2}{2g}+\frac{V_{1}^2}{2g}$$
$$(4V_{1})^2-V_{1}^2=15V_{1}^2=2g\Delta h$$
$$V_{1}=\sqrt{ \frac{2}{15}g\Delta h }=\sqrt{ \frac{2}{15}\left( 9.81 \frac{m}{s^2} \right)(.5m) }=.808 \frac{m}{s}$$
$$Q=A_{1}V_{1}=(.00785 m^2)\left( .808 \frac{m}{s} \right)=.00635 \frac{m^3}{s}$$

`<div style="page-break-after: always;"></div>
### Problem 2
$$Re=\frac{\rho V_{2}D_{2}}{\mu}=\frac{\left( 997 \frac{kg}{m^3} \right)\left( \frac{.00635 \frac{m^3}{s}}{.00196m^2} \right)(.05m)}{(.0010016Pa\cdot s)}=161285$$
This is turbulent flow because turbulent flow is characterized by a Reynold's number higher than 5000, and 161,285 is much higher than 5000.





