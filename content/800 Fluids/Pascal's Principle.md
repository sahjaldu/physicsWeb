Pascal's Principles states that:

> [[Pressure]] applied to an enclosed field is transmitted undiminished to every portion of the [[Fluids|fluid]] and to the walls of the containing vessel.

If you increase the external pressure on a fluid at one location by $\Delta p$, this change in pressure is also experienced everywhere else in the fluid.

All of hydraulics operate using Pascal's principle. It lets us amplify small forces to move massive parts.

### Proving Pascal's Principle

We will prove Pascal's principle for an uncompressible liquid.
![[Pasted image 20240130160922.png|center]]

In this example, an external for $\vec{F}$ is applies to a cylinder with a piston, bringing about at $p_{\mathrm{ext}}$ to the liquid inside. We can write the pressure at a point $P$ a distance $h$ [[Variation of Pressure for Fluids at Rest|below the surface]]:
$$
p = p_{\mathrm{ext}} + \rho gh
$$
if the external pressure is increased by $\Delta p_{\mathrm{ext}}$, then:
$$
\Delta p=\Delta p_{\mathrm{ext}}+\Delta(\rho gh)
$$
Since the liquid is incompressible, $\rho$ does not change:
$$
\Delta p = \Delta p_{\mathrm{ext}}
$$
So, the change in pressure at any point in the fluid is equal to the change in external pressure, confirming Pascal's principle.

Even though we have assumed that the liquid is incompressible in this case, Pascal's principle is true for all fluids. For compressible fluids, a change in external pressure leads to a change in density, but the disturbance fades over time and the effect is the same.

### The Hydraulic Lever

![[Pasted image 20240130183034.png|center|500]]

The Hydraulic Lever is an application of pascal's principle. In this example, an external force $F_{i}$ is applied on a piston of area $A_{i}$. On the other end, a car applies a force $Mg$ on a larger piston of area $A_{o}$. In [[Static Equilibrium; Elasticity and Fracture|equilibrium]], the two forces must be equal.

The pressure on the fluid from the small piston is $p_{i} = F_{i} / A_{i}$, and according to Pascal's Principle, this pressure is applied at every point in the fluid, including at the other fluid. As a result, the other fluid experiences an equal pressure, $p_{o} = F_{o} / A_{o}$. Therefore:
$$
\begin{align}
p_{i}&=p_{o} \\
\frac{F_{i}}{A_{i}}&=\frac{F_{o}}{A_{o}} \\
F_{i}=F_{o} \frac{A_{i}}{A_{o}}&=Mg \frac{A_{i}}{A_{o}}
\end{align}
$$
Since the ratio $A_{i} / A_{o}$ is smaller than 1, $F_{i}$ is smaller than $Mg$. When the car is lifted, the volume $V$ displaced by the movement of each liquid is the same (for an incompressible liquid).
$$
\begin{align}
V=d_{i}A_{i}=d_{o}A_{o} \\
d_{o}=d_{i} \frac{A_{i}}{A_{o}}
\end{align}
$$
Since the ratio $A_{i} / A_{o}$ is smaller than 1, similar to before, the distance moved by the large piston must be smaller than the distance moved by the small piston. Combining these equations:
$$
F_{i}d_{i}=F_{o}d_{o}
$$
