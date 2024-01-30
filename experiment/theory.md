# Introduction

Series RLC circuits consist of a resistance, a capacitance and an inductance connected in series across an alternating supply. Series RLC circuits are classed as second-order circuits because they contain two energy storage elements, an inductance L and a capacitance C. Consider the RLC circuit below. In this experiment a circuit(Fig 1) will be provided. A p-p sinusoidal signal of amplitude 3V will be applied to it and its frequency response would be verified .
<div align="center">
<img src="images/Mainckt.png" /> <br>
 
Figure 1:Circuit diagram
</div>
<br/><br/>

The above R, L, C series circuit forms a second order system.The transfer function of this circuit is given by,

 $$H(s) = \frac{\frac{1}{LC}}{s^2 + (\frac{R}{L})s + \frac{1}{LC}}$$
 
can be compared with general equation.

$$H(s) = \frac{{\omega_n}^2}{s^2 + 2 \zeta \omega_n s + {\omega_n}^2} \ where \ \omega_n \ = \frac{1}{\sqrt{LC}}$$

The gain and phase response against frequency will be typical of second order system. The expected maximum gain for each &zeta; can be observed from the plot in the experiment. Theoretical expression for obtaining maximum gain is,

$$M_m = \frac{1}{2 \omega \sqrt{1 - \zeta^2}}$$

$$Occurring \ at \ \omega_m = \omega_n \sqrt{1 - 2 \zeta^2}$$

<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
