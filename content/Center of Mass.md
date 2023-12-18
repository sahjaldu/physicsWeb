The center of mass is a point in which we can represent an entire object. This is useful for complex motion of objects,

>[!Definition]
>The center of mass is a fixed point in any solid object whose location is determined by the way the mass of the object is distributed.

Think of it as the net position of all the particles within an object.

For a system containing $N$ particles of masses $m_{1}, m_{2}, \dots$ the total mass is:
$$
M=\sum m_{n}
$$
Where the position is $\mathbf{\vec{r}_{cm}}$:
$$
\begin{align*}
\vec{r}_{cm}&=\frac{m_{1}\vec{r}_{1}+m_{2}\vec{r}_{2}+\dots+m_{N}\vec{r}_{N}}{m_{1}+m_{2}+\dots+m_{N}}\\
&=\frac{1}{M}\sum m_{n}\vec{r}_{N}
\end{align*}
$$
In components:
$$
\begin{align*}
x_{cm}&=\frac{1}{M}\sum m_{n}\vec{x}_{N} \\
x_{cm}&=\frac{1}{M}\sum m_{n}\vec{x}_{N}\\
z_{cm}&=\frac{1}{M}\sum m_{n}\vec{z}_{N}
\end{align*}
$$
Which we can use to find the velocity of center of mass:
$$
\begin{align*}
\vec{v}=\frac{ d\vec{r}_{cm} }{ dt } &=\frac{m_{1}\vec{v}_{1}+m_{2}\vec{v}_{2}+\dots+m_{N}\vec{v}_{N}}{m_{1}+m_{2}+\dots+m_{N}}\\
&=\frac{1}{M}\sum m_{n}\vec{v}_{N}
\end{align*}
$$
And the acceleration of center of mass:
$$
\begin{align*}
\vec{a}=\frac{ d\vec{v}_{cm} }{ dt } &=\frac{m_{1}\vec{a}_{1}+m_{2}\vec{a}_{2}+\dots+m_{N}\vec{a}_{N}}{m_{1}+m_{2}+\dots+m_{N}}\\
&=\frac{1}{M}\sum m_{n}\vec{a}_{N}
\end{align*}
$$
Which can be rewritten as:
$$
\begin{align*}
M\vec{a}_{cm}&=m_{1}\vec{a}_{1}+m_{2}\vec{a}_{2}+\dots m_{N}\vec{a}_{N} \\
=&\sum\vec{F}_{1}+\sum\vec{F}_{2}+\dots\sum\vec{F}_{N}
\end{align*}
$$
Which is also just:
$$
\sum \vec{F}_{\mathrm{ext}} = M\vec{a}_{\mathrm{cm}}
$$
Which means that the external forces on a system is just the forces on each particle.

>[!info]
>The overall translational motion of a system of particles can be analyzed using Newton’s laws as if all the mass were concentrated at the center of mass and the total external force were applied at that point.

>[!info]
>If the net external force on a system of particles is zero, then the center of mass of the system moves with constant velocity

For solid objects, rather than taking every single particle in the object can be represented with an integral:
$$
\vec{r}_{\mathrm{cm}}=\frac{1}{M}\int \vec{r} \, dm 
$$
[[Center of Mass Problem — Circle with Hole]]
[[Center of Mass Energy]]
