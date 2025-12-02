---
due: 2025-11-20
tags:
  - CE336
submitted: T
src:
---

### Data for Run 1
$$y_{1}=0.05ft;\quad y_{2}=0.34ft$$
$$\Delta h_{1}=13.5in;\quad \Delta h_{2}=0.40in$$
$$\text{Tank Height: }H=34in;\quad \text{Gate Opening: }0.495in$$
$$b=1ft;\quad g=32.2 \frac{ft}{s^2};\quad \rho=1.938 \frac{\text{ slug}}{ft^3};\quad \gamma=62.4 \frac{lb}{ft^3}$$
$$C_{v}=0.95$$
### Velocities
$$V_{1}=\sqrt{ 2g\Delta h_{1} }=\sqrt{ 2\left( 32.2 \frac{ft}{s^2} \right)(13.5in)\left( \frac{1ft}{12in} \right) }=8.512 \frac{ft}{s}$$
$$V_{2}=\sqrt{ 2g\Delta h_{2} }=\sqrt{ 2\left( 32.2 \frac{ft}{s^2} \right)(0.40in)\left( \frac{1ft}{12in} \right) }=1.465 \frac{ft}{s}$$

### Flow Rate
$$Q_{1}=AV_{1}=by_{1}V_{1}=(1ft)(0.05ft)\left( 8.512 \frac{ft}{s} \right)=0.426 \frac{ft^3}{s}$$
$$Q_{2}=AV_{2}=by_{2}V_{2}=(1ft)(0.34ft)\left( 1.465 \frac{ft}{s} \right)=0.498 \frac{ft^3}{s}$$
$$Q_{t}=b\left[ \frac{(y_{1}+y_{2})\sqrt{ gy_{1}y_{2} }}{2} \right]=(1ft)\left[ \frac{(0.05ft+0.34ft)\sqrt{ \left( 32.2 \frac{ft}{s^2} \right) }(0.05ft)(0.34ft)}{2} \right]=0.1443 \frac{ft^3}{s}$$
$$Q_{m}=C_{v}A\sqrt{ 2gH }=(0.95)\left( 1ft\cdot .4950in\cdot \frac{1ft}{12in} \right)\sqrt{ 2\left( 32.2 \frac{ft}{s^2} \right)(34in)\left( \frac{1ft}{12in} \right) }=0.529 \frac{ft^3}{s}$$
$$\text{Adjusted }Q=\frac{Q_{1}+Q_{2}+Q_{m}}{3}=0.484 \frac{ft^3}{s}$$

`<div style="page-break-after: always;"></div>
### Specific Energy
$$E_{1}=y_{1}+\frac{Q_{1}^2}{2gA_{1}^2}=.05ft+\frac{\left( .426 \frac{ft^3}{s} \right)^2}{2\left( 32.2 \frac{ft}{s^2} \right)(1ft)^2(.05ft)^2}=1.175ft$$
$$E_{2}=y_{2}+\frac{Q_{2}^2}{2gA_{2}^2}=.34ft+\frac{\left( 0.498 \frac{ft^3}{s} \right)^2}{2\left( 32.2 \frac{ft}{s^2} \right)(1ft)^2(.34ft)^2}=.3733 ft$$
$$\Delta E_{a}=E_{1}-E_{2}=1.175ft-.3733ft=.8017ft$$
$$\Delta E_{t}=\frac{(y_{2}-y_{1})^3}{4y_{1}y_{2}}=\frac{(.34ft-.05ft)^3}{4(.34ft)(.05ft)}=.359ft$$
$$\frac{\Delta E_{a}}{E_{1}}=\frac{.8017ft}{1.175ft}=.682$$
$$\frac{\Delta E_{t}}{E_{1}}=\frac{.359ft}{1.175ft}=.305$$

### Froude Numbers
$$\text{Fr}_{1}=\frac{V_{1}}{\sqrt{ gy_{1} }}=\frac{8.512 \frac{ft}{s}}{\sqrt{ \left( 32.2 \frac{ft}{s^2} \right)(.05ft)}}=6.708$$
$$\text{Fr}_{2}=\frac{V_{2}}{\sqrt{ gy_{2} }}=\frac{1.465 \frac{ft}{s}}{\sqrt{ \left( 32.2 \frac{ft}{s^2} \right)(.34ft) }}=.443$$

### Depth Ratio
$$\frac{y_{2}}{y_{1}}=6.8$$
$$\text{Theoretical: } \frac{y_{2}}{y_{1}}=\frac{1}{2}(\sqrt{ 1+8\text{Fr}_{1}^2 }-1)=\frac{1}{2}(\sqrt{ 1+8(6.708)^2 }-1)=9.0$$

### Specific Forces
$$F_{s_{1}}=\frac{\gamma y_{1}^2}{2}+\frac{\rho QV_{1}}{b}=\frac{\left( 32.4 \frac{lb}{ft^3} \right)(.05ft)^2}{2}+\frac{\left( 1.938 \frac{\text{ slug}}{ft^3}  \right)\left( .426 \frac{ft^3}{s} \right)\left( 8.512 \frac{ft}{s} \right)}{1ft}=7.098lb$$
$$F_{s_{2}}=\frac{\gamma y_{2}^2}{2}+\frac{\rho QV_{2}}{b}=\frac{\left( 32.4 \frac{lb}{ft^3} \right)(.34ft)^2}{2}+\frac{\left( 1.938 \frac{\text{ slug}}{ft^3}  \right)\left( .498 \frac{ft^3}{s} \right)\left( 1.465 \frac{ft}{s} \right)}{1ft}=5.021lb$$


