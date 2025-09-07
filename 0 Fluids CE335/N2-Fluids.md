---
date: 2025-09-04
tags:
  - CE335
---

## Ch. 2, Fluid Statics
hydrostatics $\to$ no shear stress (water)
Pressure is a Scalar

### proof pressure is equal regardless of direction
![[Pasted image 20250904141054.png]]
![[Pasted image 20250904141144.png]]
$$\sum dF_{y}=dF_{1}-dF_{3}\sin \theta=0=p_{1}dz-p_{3}ds \frac{dz}{ds}$$
$$p_{1}=p_{3}$$
$$\sum dF_{z}=dF_{2}-dF_{3}\cos \theta-dW=0=p_{2}dy-p_{3}ds \frac{dy}{ds}-\frac{\gamma dzdy}{2}dx$$
$$p_{2}=p_{3}+\frac{\gamma dz}{z}$$
same pressure from any direction at the same point

## Pressure Variation in finite volume of static fluid
![[Pasted image 20250904142254.png]]
![[Pasted image 20250904142307.png]]
![[Pasted image 20250904142320.png]]
![[Pasted image 20250904142337.png]]
derivation
no pressure change in x or y
as z increases pressure decreases by $\gamma$
for hydrostatic fluid @ equilibrium:
$$\frac{dp}{dz}=-\gamma$$
$$dp=-\gamma dz\to p=\int -\gamma \, dz=\gamma \Delta z $$
![[Pasted image 20250904144639.png]]

![[Pasted image 20250904144653.png]]
$$\sum F_{z}=0=F-W\to F=W$$
$$\frac{p_{1}}{\gamma}+z_{1}=\frac{p_{2}}{\gamma}+z_{2}\to p_{1}=p_{2}$$
$$\frac{F_{1}}{A_{1}}=\frac{F_{2}}{A_{2}}\to F_{1}=F_{2} \frac{A_{1}}{A_{2}}=\frac{F_{2}}{10}=200\text{ lbf} $$


![[Pasted image 20250904144713.png]]


![[Pasted image 20250904144727.png]]
since theyre connected, there is hydrostatic equilibrium 
$$p_{1}=p_{2}$$
$$p_{3}<p_{4}$$

![[Pasted image 20250904144739.png]]

![[Pasted image 20250904144753.png]]

![[Pasted image 20250904144814.png]]


