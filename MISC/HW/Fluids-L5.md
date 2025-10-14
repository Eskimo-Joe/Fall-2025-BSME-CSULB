---
due: 2025-10-09
tags:
  - CE336
submitted: T
src:
---

### Pipe Size
$$D=4.37mm=.00437m;\quad A=\frac{\pi}{4}D^2=.000015m^2$$
### Flow Rate
$$V=.25L;\quad t=14.74s;\quad Q=\frac{V}{t}=\frac{.25L}{14.74s}\left( \frac{1m^3}{1000L} \right)=.000017 \frac{m^3}{s}$$
### Velocity
$$Q=Av\to v=\frac{Q}{A}=\frac{.000017 \frac{m^3}{s}}{000015m^2}=1.13 \frac{m}{s}$$
### Reynold's Number
$$Re=\frac{vD}{\nu}=\frac{\rho vD}{\mu}=\frac{\left( 1000 \frac{kg}{m^3} \right)\left( 1.13 \frac{m}{s} \right)(.00437m)}{.001002 Pa\cdot s}=4933.1$$
`<div style="page-break-after: always;"></div>
### Friction Factors
$$f_{expected}=\frac{64}{Re}=.01297;\quad f_{moody}\approx.036$$
### Expected Head Loss
$$h=f\frac{Lv^2}{2Dg}=.036\left( \frac{(1m)\left( 1.13 \frac{m}{s} \right)^2}{2(.00437m)\left( 9.81 \frac{m}{s^2} \right)} \right)=.5376m$$
### Measured Head Loss
$$h_{m}=.630m$$
### Percent Error
$$\text{Error}=\frac{abs(h_{m}-h)}{h_{m}}=\frac{.630-.5376}{.630}=14.8\%$$

