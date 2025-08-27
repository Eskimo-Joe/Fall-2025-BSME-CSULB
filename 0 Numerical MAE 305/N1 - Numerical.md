---
date: 2025-08-26
tags:
  - MAE305
src: https://csulb.instructure.com/courses/105733/files/24936644?module_item_id=6273686
---

## sources of error
1. Truncation 
2. Round-off
	1. Addition and sub
	2. non-terminating numbers
3. Propagating (multiplying)

![[Pasted image 20250826161635.png|400]]

![[Pasted image 20250826161650.png]]

![[Pasted image 20250826161703.png]]

![[Pasted image 20250826161711.png]]

![[Pasted image 20250826161720.png]]

## taylor series
![[Pasted image 20250826162944.png]]
$$x=.01;\quad x=x_{0}+h;\quad h=.01$$
Calculated = 1.01
True = 1.010050167
True error =  .000050167

## error definition
True Error
$$E_{t}=\text{True Value} - \text{calculated value}$$
True percent relative error: 
$$\epsilon_{t}=\frac{True-calculated}{true}$$
Approximate percent relative error
$$\epsilon_{a}=\frac{Present-Previous}{Present}$$
Stopping Criteria: $\epsilon_{s}$
$$\epsilon_{a}<\epsilon_{s}$$
