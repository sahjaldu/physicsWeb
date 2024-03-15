As an [[Ideal Fluid]] flows through a pipe or [[Streamlines and Tubes of Flow#Tubes of Flow|Tube of Flow]], it can change in several ways:
- The cross sectional area might change.
- The inlet and outlet may be at different elevations
- The inlet and outlet pressures may be different.

Using the [[Equations of Continuity|Equation of Continuity]] for fluid flow:
$$
A_{1}v_{1}=A_{2}v_{2}
$$
We related change in area to changes in velocity. Change in [[pressure]] and elevation are both related to velocity, so each type are not independent of each other.
### Deriving Bernoulli's Equation

Lets use an example of a pipe:
![[Pasted image 20240208194137.png|center|500]]
The pipe has cross-sectional area $A_{1}$ and elevation $y_{1}$ at the inlet and cross-sectional area $A_{2}$ and elevation $y_{2}$ at the end. Because the area changes, the velocity changes from $v_{1}$ to $v_{2}$.

We will use [[Conservation of Energy]] to the [[Systems of Particles|system]] of the fluid between the inlet and outlet.

Lets say that there may be a pressure $p_{1}$ from additional fluid on the left and a pressure $p_{2}$ from additional fluid on the right. This means there are forces $F_{1}=p_{1}A_{1}$ and $F_{2}=p_{2}A_{2}$.

Under both forces and gravity, we will say that the system moves to the right. The figure below shows the system after a time $\delta t$.
![[Pasted image 20240208194823.png|center|500]]
In this time, the left side has moved an $\delta x_{1}$ and the right $\delta x_{2}$. These distances are different because of the difference in areas. The same effect would have been reached had we taken out the shaded section of mass $\delta m$ from the inlet and placed it at the outlet.

There are three factors for the net [[Work Done on a System By External Forces|External Work]].
1. At the inlet, the pressure force is:
$$
W_{1}=F_{1}\delta x_{1}=p_{1}A_{1}\delta x_{1}
$$
2. At the outlet, the pressure force is:
$$
W_{2}=-F_{2}\delta x_{2}=-p_{2}A_{2}\delta x_{2}
$$
3. Work done by gravity as a fluid element $\delta m$ moves through vertical displacement $y_{2}-y_{1}$:
$$
W_{g}=-\delta m\,g(y_{2}-y_{1})
$$
In [[Conservation of Energy]], $\Delta U$ is the [[Potential Energy]] from [[Conservative Force|Conservative Forces]] that act between objects in the system. Since our fluid is ideal, we assume there are no such forces, so $\Delta U=0$.

The net external [[Work]] would be:
$$
\begin{align}
W_{\mathrm{ext}}&=W_{1}+W_{2}+W_{g} \\
&=p_{1}A_{1}\delta x_{1}-p_{2}A_{2}\delta x_{2}+[-\delta m\,g(y_{2}-y_{1})]
\end{align}
$$
The volume of the shaded fluid element $\delta V$ can be written as $\delta V=A_{1}\delta x_{1}$ and $\delta V=A_{2}\delta x_{2}$, since the fluid is incompressible. The uniform and constant fluid density is $\rho$ and so we can also rewrite our element as $\delta V=\delta m / p$. Substituting:
$$
W_{\mathrm{ext}}=(p_{2}-p_{1})(\delta m / p)-\delta m\,g(y_{2}-y_{1})
$$
The change in [[Kinetic Energy]] for $\delta m$ is:
$$
\Delta K=\frac{1}{2}\delta v\,v^2_{2}-\frac{1}{2}\delta m\,v^2_{1} 
$$
Applying conservation of energy:
$$
\frac{1}{2}\delta v\,v^2_{2}-\frac{1}{2}\delta m\,v^2_{1} =(p_{2}-p_{1})(\delta m / p)-\delta m\,g(y_{2}-y_{1})
$$
And rearranging/cancelling:
$$
p_{1}+\frac{1}{2}\rho v^2_{1}+\rho gy_{1}=p_{2}+\frac{1}{2}\rho v^2_{2}+\rho gy_{2}
$$
Or:
$$
\boxed{p+\frac{1}{2}\rho v^2+\rho gy=\text{constant}}
$$
This is Bernoulli's Equation for ideal fluids, which state that the equation above is constant along a streamline.

### Analyzing Bernoulli's Equation

As we've seen, Bernoulli's Equation is a derivation of conservation of energy. We can split it into types of energies:

- $p$ is the Pressure Energy
- $\frac{1}{2}\rho v^2$ is the Kinetic Energy
- $\rho gy$ is the Potential Energy

### Special Applications

1. Static [[Pressure]].

Static Pressure is simply a case where velocity is 0.
$$
\begin{align}
p_{1}+\frac{1}{2}\rho v^2_{1}+\rho gy_{1}&=p_{2}+\frac{1}{2}\rho v^2_{2}+\rho gy_{2} \\
p_{1}+\rho gy_{1}&=p_{2}+\rho gy_{2} \\ p_{2}-p_{1}&=-\rho g(y_{1}-y_{1}) \\
&=-\rho gh
\end{align}
$$
Which matches the equation we derived in [[Variation of Pressure for Fluids at Rest]].
<br>
2. Dynamic Pressure.

Suppose a fluid flowing horizontally, so there is no difference in elevation:
$$
\begin{align}
p_{1}+\frac{1}{2}\rho v^2_{1}+\rho gy_{1}&=p_{2}+\frac{1}{2}\rho v^2_{2}+\rho gy_{2} \\
p_{1}+\frac{1}{2}\rho v^2_{1}&=p_{2}+\frac{1}{2}\rho v^2_{2}
\end{align}
$$
In this equation, as the speed is large,  pressure must be small, and vice versa. The quantity $\frac{1}{2}\rho v^2$ is called the dynamic pressure.
<br>
3. Compressible, viscous flow.

If the fluid is compressible, then its [[Internal Energy in A System of Particles|Internal Potential Energy]] $\Delta U_{\mathrm{int}}$ can change as molecules become closer and further apart.

If the flow is viscous, then the internal kinetic energy $\Delta K_{\mathrm{int}}$ can change, similar to how [[Frictional Work|Frictional]] forces increase the internal energy.

Our complete analysis should include internal energy:
$$
\Delta E_{\mathrm{int}} = \Delta U_{\mathrm{int}} + \Delta K_{\mathrm{int}}
$$
or:
$$
\Delta K+\Delta E_{\mathrm{int}} = W_{\mathrm{ext}}
$$
If necessary, Bernoulli's equation could be modified to account for theses other energy transformation.

### Other Applications
[[The Venturi Meter]]
[[The Pilot Tube]]
[[Dynamic Lift]]
[[Thrust on a Rocket]]
