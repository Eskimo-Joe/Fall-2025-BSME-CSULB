---
tags:
  - MAE336
date: 2025-09-30
---

Objectives
- evaluate performance of gas power cycles where fluid is gas throughout the cycle
- develop simplifying asumpts applicable to has power cycles
- reviewthe operation of reciprocating engines
- analyze both closed and open gas power cycles
- solve problmes based in Otto, Diesel, Stirling, and Ericsson cycles
- Solve problems based on Brayton cycle; Brayton with regeneration; Brayton cycle with intercooling, reheating, and regeneration
- analyze jet-propulsion cycles
- identify simplifying assumptions for 2nd law analysis of gas power cycles

thermal efficiency of heat engines (lower than Carnot)
$$\eta=\frac{W_{net}}{Q_{in}}=\frac{w_{net}}{q_{in}}$$

ideal cycles can be internally reversible
but not externally reversible

idealizations ignore friction and pressure drop in 
expansion and compression are in quasi-equilibrium
pipes are well insulated


## 10-02

brief summary of previous lecture

Compression Ration
$$r= \frac{v_{max}}{v_{min}}=\frac{v_{BDC}}{v_{TDC}}$$

BDC - TDC = stroke

- Spark ignition (SI) engine
- Compression ignition (CI) engine

spark ignition is petrol
compression ignition is diesel

$$W_{net}=MEP\times \text{Pison Area}\times \text{Stroke}=MEP\times \text{Displacement volume}$$
$$MEP=\frac{W_{net}}{V_{max}-V_{min}}=\frac{w_{net}}{v_{max}-v_{min}}$$
MEP = Mean effective pressure 

OTTO CYCLE: ideal cycle for SI engines

four stroke vs two stroke
4 stroke has two revs per cycle
2 stroke has one rev per cycle

$$q_{in}-q_{out}+w_{in}-w_{ou}=h_{exit}-h_{inlet}$$
$$q_{in}=u_{3}-u_{2}=c_{v}(T_{3}-T_{2})$$
$$q_{out}=u_{4}-u_{1}=c_{v}(T_{4}-T_{1})$$
$$\eta_{th,Ot\to }=\frac{w_{net}}{q_{in}}=1-\frac{q_{out}}{q_{in}}=1-\frac{T_{4}-T_{1}}{T_{3}-T_{2}}=1-\frac{T_{1}\left( \frac{T_{4}}{T_{1}}-1 \right)}{T_{2}\left( \frac{T_{3}}{T_{2}}-1 \right)}$$
$$\frac{T_{1}}{T_{2}}=\left(  \frac{v_{2}}{v_{1}} \right)^{k-1}=\left( \frac{v_{3}}{v_{4}} \right)^{k-1}=\frac{T_{4}}{T_{3}}$$
$$r=\frac{v_{max}}{v_{min}}=\frac{v_{1}}{v_{2}}$$

Diesel Cycle:
only air is compressed in compression stroke eliminating possibility of engine knock
results in a higher compression ratio than SI engines, from 12-24

$$q_{in}=h_{3}-h_{2}=c_{p}(T_{3}-T_{2})$$
$$q_{out}=u_{4}-u_{1}=c_{v}(T_{4}-T_{1})$$
$$\eta_{th,Diesel}=\frac{w_{net}}{q_{in}}=1-$$
...


Dual Cycle
more realistic ideal cycle for modern high speed compression ignition engine

a fifth part of the cycle is added improving accuracy

Stirling Cycle
regenerates between isentropic phases

Ericsson cycle
regenerated between constant temp phases

brayton cycle: ideal cycle for gas turbine engines
aka CTG
can be open or closed systems

cogeneration aka trigeneration
reuse heat in turbine for another gen system
and further use heat for thermal systems (HVAC) 

$$q_{in}=h_{3}-h_{2}=c_{p}(T_{3}-T_{2})$$
...


## 10-07






