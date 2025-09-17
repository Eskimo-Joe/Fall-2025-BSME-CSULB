---
due: 2025-09-18
tags:
  - CE335
submitted: T
src: https://csulb.instructure.com/courses/99910/assignments/1439813
---

## 1
An open rectangular tank is 3m wide and 5m long. The tank contains water to a depth of 3m and oil (SG = 0.8) on top of the water to a depth of 1m. Determine the magnitude of the resultant fluid force acting on the smaller end of the tank. 

$$F_{net}=F_{W}+F_{Oil}$$
Pressure at 1m:
$$p_{1m}=\rho_{oil}gh_{oil}=0.8\left( 1000 \frac{kg}{\text{ m} ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(1\text{ m} )=7.85 \text{ kPa} $$
Pressure at 4m:
$$p_{4m}=p_{1m}+\rho_{w}gh_{w}=7.85 \frac{kN}{\text{ m} ^2}+\left( 1000 \text{ kPa}  \right)\left( 9.81 \frac{m}{s^2} \right)(3\text{ m} )=37.28 \text{ kPa} $$
Total Oil Force
$$F_{oil}=p_{oil}A_{oil}=\frac{1}{2}(7.85\text{ kPa} )(3\text{ m} \times1\text{ m} )=11.77\text{ kN} $$
Total Water Force
$$F_{w}=p_{w}A_{w}=\frac{1}{2}(7.85\text{ kPa} +37.28\text{ kPa} )(3\text{ m} \times 3\text{ m} )=203.07\text{ kN} $$
Total Force
$$F=F_{oil}+F_{w}=11.77+203.07=214.84\text{ kN} $$
![[Pasted image 20250912210310.png|400]]


## 2 
A rectangular gate that is 2m wide is located in the vertical wall of a tank containing water as shown in the figure below. It is desired to have the gate open automatically when the depth of water above the top of the gate reaches 12m. a) at what distance, d, should the frictionless horizontal shaft be located? b) What is the magnitude of the force on the gate when it is closed?

Pressure at 12m
$$p=\left( 1000 \frac{kg}{\text{ m} ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(12m)=117.72\text{ kPa} $$
Pressure at 16m
$$p=\left( 1000 \frac{kg}{\text{ m} ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(16\text{ m} )=156.96\text{ kPa} $$
Finding Centroid

| n      | A      | y     | Ay      |
| ------ | ------ | ----- | ------- |
| 1      | 470.88 | 2 m   | 941.76  |
| 2      | 78.48  | 8/3 m | 209.28  |
| $\sum$ | 549.36 | -     | 1151.04 |
$$d=\frac{\sum Ay}{\sum A}=\frac{1151.04}{549.36}=2.095\text{ m} $$

Total Force
$$F=pA=\frac{1}{2}(156.96+117.72\text{ kPa} )(4\text{ m} \times2\text{ m} )=1098.72\text{ kN} $$

![[Pasted image 20250912211855.png|400]]


## 3
A U-tube manometer is used to check the pressure of natural gas entering a furnace. One side of the manometer is connected to the gas inlet line, and the water level in the other side open to atmospheric pressure rises 3.4in. What is the gage pressure of the natural gas in the inlet line in inH2O and in psf gage?

$$p_{gas}=6.8 inH_{2}O$$
$$p_{gas}=\gamma_{w}h_{w}=\left( 62.4 \frac{lb}{ft^3} \right)\left( \frac{2\cdot 3.4}{12}ft \right)=35.4psf $$

![[Pasted image 20250912212818.png|400]]


## 4
A Hg manometer is connected to a large reservoir of water as shown in the figure below. Determine the ratio hw/hm of the distances hw and hm indicated in the figure. 

$$p_{w}+p_{a}=p_{m}+p_{a}$$
$$\gamma_{w}h_{w}+\gamma_{w}h_{m}=2\gamma_{m}h_{m}$$
$$h_{w}+h_{m}=\frac{2\gamma_{m}h_{m}}{\gamma_{w}}\to h_{w}=\frac{2\gamma_{m}h_{m}}{\gamma_{w}}-h_{m}$$
$$\frac{h_{w}}{h_{m}}=2SG_{m}-1=2(13.6)-1=26.2$$
![[Pasted image 20250912213615.png|400]]


## 5
A piston having a cross-sectional area of 0.03m^2 is located in a cylinder containing water as shown in the figure below. An open U-tube manometer is connected to the cylinder as shown. For h1=120mm and h=200mm, what is the value of the applied force, P, acting on the piston? The weight of the piston is negligible. 

$$\frac{P}{A}+\gamma_{w}h_{1}=\gamma_{Hg}h$$
$$P=A(\gamma_{Hg}h-\gamma_{w}h_{1})$$
$$P=(.03\text{ m} ^2)[13.6\left( 1000 \frac{kg}{\text{ m} ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(.2\text{ m} )-\left( 1000 \frac{kg}{\text{ m} ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(.12\text{ m})]$$
$$P=765.18\text{ N} $$
![[Pasted image 20250912214908.png|400]]


## 6
A homogenous, 4-ft-wide, 10-ft-long rectangular gate weighing 800lb is held in place by a horizontal flecible cable as shown in the figure below. Water acts against the gate, which is hinged at point A. Friction in the hinge is negligible. Determine the tension in the cable. Assume L1=10ft, L2=9.9ft, and $\theta$ = 75deg.

Water height
$$ h_{w}=L_{2}\sin(\theta)=9.9ft(\sin(75^{\circ} ))=9.56\text{ ft}  $$
Bottom Pressure
$$p=\gamma_{w}h_{w}=\left( 62.4 \frac{\text{ lb} }{\text{ ft} ^3} \right)(9.56ft )=596.71\text{ psf} $$
Sum of moments
$$\sum M=0\to M_{t}=M_{w}+M_{g}$$
$$F_{T}=\frac{M_{w}+M_{g}}{L_{1}\sin(\theta)}=\frac{\frac{p_{w}}{2} A_{w}\cdot \frac{L_{2}}{3}+W\cdot \frac{L_{1}}{2}\cos\theta}{L_{1}\sin \theta}$$
$$F_{T}=\frac{\frac{1}{6}(596.7\text{ psf} )(4\text{ ft} \times 9.9\text{ ft} )(9.9\text{ ft} )+ \frac{1}{2}(800lb)(10ft)\cos(75^{\circ})}{10ft\sin(75^{\circ})}$$
$$F_{T}=4143.6\text{ lb}$$
![[Pasted image 20250912221024.png|400]]


## 7
Find the magnitude and location of the net horizontal force on the gate shown in the figure below. The gate width is 3.5m. 

$$F=\left( 1000 \frac{kg}{m ^3} \right)\left( 9.81 \frac{m}{s^2} \right)(1\text{ m} )(2\text{ m} \cdot 3.5\text{ m} )=68.7\text{ kN} $$

![[Pasted image 20250912222615.png|400]]

	


