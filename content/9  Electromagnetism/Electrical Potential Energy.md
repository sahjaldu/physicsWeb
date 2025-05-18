One can find the work from the Electric Force from $\vec{r}_{i}$ to $\vec{r}_{f}$.
$$
\begin{align}
\vec{F}  & =k \frac{q_{1}q_{2}}{r^{2}} \hat{r} \hspace{ 0.3in } W = \int_{1}^{2} \vec{F} \cdot \,d\vec{r} \\
\vec{F}_{0} & = k \frac{q_{1}Q}{r^{2}} \hat{i}_{r} \hspace{ 0.3in } d\vec{r} = dr \hat{i}_{r} + r\, d\theta \hat{i}_{\theta} \tag{1}  \\
W & = \cancelto{ 0 }{ \int_{r_{i},\theta_{i}}^{r_{i},\theta_{f}} k \frac{q_{0}Q}{r^{2}} \hat{i}_{r} \cdot \, rd\theta \hat{i}_{\theta}  }+ \int_{r_{i},\theta_{f}}^{r_{f},\theta_{f}} k \frac{q_{0}Q}{r^{2}} \hat{i}_{r}  \, dr \hat{i}_{r}  \\
 & = kq_{0}Q \int _{r_{i}}^{r_{f} } \frac{1}{r^{2}} \, dr = -kq_{0}Q\left[ \frac{1}{r_{f}}-\frac{1}{r_{i}} \right] \\
 & = \boxed{ kq_{0}Q\left[ \frac{1}{r_{i}}-\frac{1}{r_{f}} \right] }
\end{align}
$$
$(1)$ This comes from $\frac{ d\vec{r} }{ dt }= \frac{ dr }{ dt } \hat{i}_{r} + r \frac{ d \theta }{ d t }\hat{i}_{\theta}$.

Since the Electric Force is a [[Conservative Force]], there exists a valid potential energy function.
$$
U = -k \int \frac{q_{1}q_{2}}{r^{2}}\,dr = k \frac{q_{1}q_{2}}{r}\cancelto{ 0 }{ +C }
$$

>[!quote]
>"Electric potential energy is the energy required to move a charge against an electric field." (Khan Academy)

Some other definitions:
- The [[Energy]] stored in the [[Systems of Particles|arrangement]] of charges particles.
- The negative of the [[Work]] done by the conservative force the force of the electric field to arrange the charges.

The formula is similar to [[Coulomb's Law]], but with $r$ instead of $r^2$:
$$
U_{E}=\frac{1}{4\pi\epsilon_{0}}\frac{q_{1}q_{2}}{r}
=k\frac{q_{1}q_{2}}{r}
$$
This is also similar to the equation for [[Gravitational Potential Energy]]:
$$
U_{G}=-G \frac{m_{1}m_{2}}{r}
$$
We can relate [[Coulomb's Law|Electric Force]] to Electric Potential Energy:
$$
\Delta U_{E}=-\int \vec{F}_{E} \, d\vec{r} 
$$

>[!note]
>Potential Energy is **ALWAYS** the difference between two configurations. Sometimes you will see it as $\Delta U_{E}$ or $U_{E}$. When it doesn't have the delta, we are just assuming that one configuration is when objects are separated by infinite distance, and the potential energy is zero in that configuration.

A positive [[Potential Energy]] represents charges with a net repulsive force, and a negative potential energy represents charges with a net attractive force.

Electric Potential Energy is measured in $\mathrm{J}$ (Joules).