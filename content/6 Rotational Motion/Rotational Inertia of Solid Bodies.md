A solid body is made up of a number of particles. We can calculate its rotational inertia by taking the sum of the rotational inertias of each particle.

To do so, imagine the body divided into a large number of small mass elements $\delta m_{n}$ each located a perpendicular distance $r_{n}$ from the axis of rotation. Our rotational inertia is:
$$
I=\sum r_{n}^2\delta m_{n}
$$
If we make the size of each mass element smaller and smaller, we can transition to calculus:
$$
\begin{align*}
I=\lim_{ \delta m_{n} \to 0 } \sum r_{n}^2\delta m_{n} \\
 \\
\boxed{I=\int r^2 \, dm} 
\end{align*}
$$
We can use this to create varying formulas for different types of solid bodies.

![[Pasted image 20231211180947.png|center]]

### For example, for a rod:

![[Pasted image 20231211164235.png|center]]

The rod has a length $L$, cross-sectional area $A$, and uniform density $\rho$.
$$
\begin{align*}
dV=Adx \\
dm=\rho\ dV=\rho A\ dx \\
\rho=\frac{M}{V} =\frac{M}{AL} \\
 \\
I=\int r^2 \, dm=\int x^2\rho A \, dx =\int x^2 \frac{M}{AL} A \, dx=\frac{M}{L}\int x^2 \, dx \\
 \\
I=\frac{M}{L}\int _{-L/2}^{+L/2}x^2 \, dx =\frac{m}{L} \frac{x^3}{3} \Big \rvert_{-L / R}^{+L / 3} \\
 \\
\boxed{I=\frac{1}{12}ML^2}
\end{align*}
$$
If we want to rotate the rod about its end, use the [[Parallel Axis Theorem]] substituting this for $I_{\mathrm{cm}}$.
$$
\frac{1}{2}ML^2+M\left( \frac{L}{2} \right)^2=\frac{1}{3}ML^2
$$
### Or for a plate:
We can divide the plate into a series of strips where we consider each to be a rod.

![[Pasted image 20231211175159.png|center]]

Note that the plate has extremely small height; this picture shows a large amount.

The mass of the strip $dm$ is related to total mass $M$ like how the surface area of the strip $a dx$ is related to the total surface area $ab$:
$$
\frac{dm}{M}=\frac{a\ dx}{ab}=\frac{dx}{b}
$$
The rotational inertia $dI$ of a strip about its [[Center of Mass]] is $dI_{\mathrm{cm}}=\frac{1}{12}dm\ a^2$:
$$
\begin{align*}
dI&=dI_{\mathrm{cm}}+dm\ h^2 \\
&=\frac{1}{12}dm\ a^2+dm\ x^2
\end{align*}
$$
Substituting $dm$ for $M$ and $dx$ for $b$:
$$
dI=\frac{Ma^2}{12b}dx+\frac{M}{b}x^2dx
$$
Taking the integral from $-b/2$ to $+b/2$:
$$
\boxed{
I=\frac{1}{12}M(a^2+b^2)
}
$$
We can continue using this method for a cube using a stack of plates, etc. 