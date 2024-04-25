On this page, we will look at fluids in [[Static Equilibrium; Elasticity and Fracture|Equilibrium]], meaning that every portion of the fluid has both net force and net [[Torque]] equal zero.

Consider a small portion of fluid within the greater body of a homogeneous fluid. The element should be shaped like a thin disk with height $dy$ and area $A$.

The mass of the element would be:
$$
dm=\rho \,dV=\rho A\,dy
$$
and the weight would be:
$$
(dm)g=\rho gA\,dy
$$
The disk has no horizontal forces, and since the element is at equilibrium, its vertical forces must be net zero.

Lets define some more variables:
- $p$ is the [[pressure]] on the lower face.
- $p+dp$ is the pressure on the upper face. We add the $dp$ due to change in pressure from the height $dy$.
- $pA$ is the upward force on the lower face since $pA=\frac{F}{A}A$.
- $(p+dp)A$ is the downward force on the upper face for the same reason.

So, for the vertical forces:
$$
\sum F_{y}=pA-(p+dp)A-\rho gA\,dy=0
$$
From which we get:
$$
\begin{align}
pA-(p+dp)A-\rho gA\,dy&=0 \\
pA-pA-dp\,A&=\rho gA\,dy \\
-\frac{ dp }{ dy } &= -\frac{\rho gA}{A} \\
\Aboxed{\frac{ dp }{ dy } &= -\rho g}
\end{align}
$$
We can use this equation to tell us how pressure changes from elevation above a certain point.

>[!info]- 
> $\rho g$ is also known as the weight density of a fluid, the weight per volume of a fluid.
> $$\rho g=\frac{mg}{V}$$

We can integrate this to find pressure at a certain point:
$$
\begin{align}
\int _{p_{1}}^{p_{2}} \, dp &=-\int ^{y_{2}}_{y_{1}}\rho g \, dy  \\
p_{2}-p_{1}&=-\rho g(y_{2}-y_{1})
\end{align}
$$
Liquids rarely compress, so we can keep $\rho$ constant as we integrate.

We can manipulate the equation further for instances where the liquid is being held in a regular container, such as a beaker:
$$
\begin{align}
p_{2}-p_{1}&=-\rho g(y_{2}-y_{1}) \\
p_{0}-p&=-\rho g(y_{2}-y_{1}) \\
\Aboxed{p&=p_{0}+\rho gh}
\end{align}
$$
The pressure is dependent on the depth, $h$, below the surface.

For more weirdly shaped containers, we use our original equation, $p_{2}-p_{1}=-\rho g(y_{2}-y_{1})$. This equation can be used to find the difference in pressures for any two points. For example, for a U-tube:

![[Pasted image 20240119200854.png|center]]

For the change in pressure between points A and B, we just sum the vertical segments between A and B and multiply it by $\rho g$.

### Variation of Pressure in the Atmosphere

For gases, the density, $\rho$, is relatively small, so the difference between two points is negligible. As a result, for a gas in a container we can say the pressure is the same everywhere. Yet if the distance is great enough, such as in earth's atmosphere, $\rho$ matters and pressure changes.

We can get a good idea for this by assuming density is proportional to pressure.^[Normally this is the case, but for the atmosphere temperature also matters.]
$$
\frac{ dp }{ dy } =-\rho g
$$
Since density is proportional to pressure:
$$
\frac{\rho}{\rho_{0}}=\frac{p}{p_{0}}
$$
Using this:
$$
\begin{align}
\frac{ dp }{ dy } &=-g\rho_{0} \frac{p}{p_{0}} \\
\frac{dp}{p} &= -\frac{g\rho_{0}}{p_{0}}dy \\
\int _{p_{0}}^{p} \frac{dp}{p} \, dy &= -\int _{0}^h \frac{g\rho_{0}}{p_{0}} \, dy   \\
\ln \frac{p}{p_{0}}&=-\frac{g\rho_{0}}{p_{0}}h \\
p&=p_{0}e^{\Large-(g\rho_{0 / p_{0}})h} \\
p&=p_{0}e^{-h / a}
\end{align}
$$
where $a = p_{0} / g \rho_{0}$. $p_{0}$ and $\rho_{0}$ are the pressure and density at sea level, so $a$ is a constant.

Note that the pressure drops by a factor of $e$. In other words, the atmospheric pressure drops by a factor of $10$ when the altitude changes by $a$.