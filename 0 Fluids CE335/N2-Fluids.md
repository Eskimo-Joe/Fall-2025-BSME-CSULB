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

## Atmospheric Pressure

$$p_{atm}=14696psia=2116.2psfa=101.33\text{ kPa}  $$

$$\gamma_{water}=\frac{62.41\text{ lbf}}{\text{ ft}^3}=9.798 \frac{kN}{\text{ m} ^3}$$
$$\gamma_{Hg}=13.57\gamma_{W}=846.9 \frac{lb}{ft^3}=132.96 \frac{kN}{ft^3}$$
$$h_{atm}=33.91ft H_{2}O=10.34m H_{2}O=29.99inHg=762.1mmHg$$

for a barometer 
$$\frac{p_{1}}{\gamma_{Hg}}+z_{1}=\frac{p_{2}}{\gamma_{Hg}}+z_{2}$$
$$p_{2}=\gamma_{hg}(z_{1}-z_{2})$$

$$1torr=1mmHg$$

## Absolute Pressure
pressure with respect to complete vacuum
gage pressure
$$p_{abs}=p_{gage}+p_{atm}$$

vacuum pressure
$$p_{v}=-p=p_{atm}-p_{abs}$$

![[Pasted image 20250909142649.png]]

manometry
![[Pasted image 20250909142740.png]]
important to determine horizontal line of equal pressure
so point 2 and 3 can be used. left side of equation is above 2 and right side is above 3. disregard below the planes

![[Pasted image 20250909144139.png]]

increase accuracy by slanting the tubes or choosing low $\gamma_{2}$ value liquid (not mercury) 

![[Pasted image 20250909144151.png]]
aka differential manometer

"handshake"
![[Pasted image 20250909145322.png]]

another example i didnt record

pressure in pipe with oil
![[Pasted image 20250909145342.png]]

see photo

## Hydrostatic Forces on a plane

![[Pasted image 20250911140607.png]]
![[Pasted image 20250911140617.png]]

![[Pasted image 20250911140635.png]]
![[Pasted image 20250911140646.png]]
![[Pasted image 20250911140706.png]]

![[Pasted image 20250911144239.png]]

![[Pasted image 20250911144246.png]]

![[Pasted image 20250911144307.png]]

$$p=4\text{ psi} $$
$$2+2 = 4$$
$$\frac{8}{32} = \frac{1}{4}$$
$$f(x):=e^{x}+2x^2$$
$$f(6) = 72 + e^{6}$$
$$p:= \frac{\rho}{R\cdot T}$$
$$R:=2$$
$$T:=3$$
$$\rho:=4$$
$$p = \frac{2}{3}$$
$$v:= 2 \, \frac{{m}}{{s}}$$
$$a:= \frac{1}{3} \, \frac{{m}}{{s}^{2}}$$
$$F:= \frac{2}{3} \, {N}$$
$$G=3000\cdot F = 2000 \, {N} $$
$$W=F\cdot 9{m} = 6 \, {J}$$
$$P=\frac{6{J}}{3{s}} = 2 \, {W}$$

$$P=2{W} = 2000 \, {mW}$$

$$P=1{W}$$


