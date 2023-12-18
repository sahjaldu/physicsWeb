Depending on how we define our system, our problem can turn from constant mass to variable mass. For example, a cannon with a cart shooting cannonballs. If our system includes the cannon, cart, and cannonballs, the mass is constant. However, if we only include the cannon and cart, the mass will decrease with each cannonball shot.

We can call our full system of the cannon, cart, and cannonballs $S'$ and call our subsystem of the cannon and cart $S$. When we shoot our cannonball, the mass $M$ of $S$ changes to $M+\Delta M$ (Where in our situation $\Delta M$ is negative) and ejects a mass (our cannonball) $-\Delta M$. $S$ moves at a new velocity $\vec{v}+\Delta \vec{v}$ and the ejected mass moves at a velocity $\vec{u}$.

![[Pasted image 20231210235731.png|center]]

Lets also introduce an external force such as drag to give a more general equation. For a change in time $\Delta t$, the change of momentum for $S'$ can be represented as:
$$
\begin{align*}
&\Delta \vec{P}=\vec{P}_{f}-\vec{P}_{i} \\ \\

&\vec{P}_{i}=M\vec{v} \\
&\vec{P}_{f}=(M+\Delta M)(\vec{v}+\Delta \vec{v})+(-\Delta M)u \\
 \\
&\Delta \vec{P}=(M+\Delta M)(\vec{v}+\Delta \vec{v})+(-\Delta M)u-M\vec{v}
\end{align*}
$$
We can calculate for external force from here:
$$
\begin{align*}
\Sigma \vec{F}_{\mathrm{ext}}&=\lim_{ \Delta t \to 0 } \frac{\Delta \vec{P}}{\Delta t} \\
&=\lim_{ \Delta t \to 0 } \frac{(M+\Delta M)(\vec{v}+\Delta \vec{v})+(-\Delta M)u-M\vec{v}}{\Delta t} \\
&=\lim_{ \Delta t \to 0 } \left[ M \frac{\Delta \vec{v}}{\Delta t}+(\vec{v}+\vec{u}) \frac{\Delta M}{\Delta t}+\Delta \vec{v} \frac{\Delta M}{\Delta t} \right] \\
&=M\frac{ d\vec{v} }{ dt }  + (\vec{v}+\vec{u})\frac{ dM }{ dt } 
\end{align*}
$$
rewritten as:
$$
\boxed{M\frac{ d\vec{v} }{ dt }=\sum\vec{F}_{\mathrm{ext}}+\vec{v}_{\mathrm{rel}}\frac{ dM }{ dt }  }
$$
Where $\vec{v}_{\mathrm{rel}}$ is the velocity of the gained or lost matter relative to subsystem $S$. If $S$ is a rocket, $\vec{v}_{\mathrm{rel}}$ is the velocity of the ejected gases relative to the rocket. The term $\vec{v}_{\mathrm{rel}}\frac{ dM }{ dt }$ is called the *thrust* of the rocket.

Notice that when the change in mass is zero, aka when $\frac{ dM }{ dt }=0$, our equation becomes $\Sigma \vec{F}_{\mathrm{ext}}=m\vec{a}$.
