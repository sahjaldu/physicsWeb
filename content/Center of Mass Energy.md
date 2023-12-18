Lets use the example of a skater pushing herself off the railing of an ice rink. The skater cannot be represented with a single particle, as her arms and body move differently, so we need a [[Systems of Particles]] to do so.
![[Pasted image 20231216010213.png|center]]
We can apply Energy Principles such as [[Conservation of Energy]] in this situation. There is no [[Potential Energy]], so $\Delta U=0$. Our equation is:
$$
\Delta K+\Delta E_{\mathrm{internal}}=0
$$
Where $\Delta K$ is change in [[Kinetic Energy]] and $\Delta E_{\mathrm{internal}}$ is Change in the [[Internal Energy in A System of Particles]]. Since the skater moves from rest, $\Delta K=\Delta\left( \frac{1}{2}Mv_{\mathrm{cm}}^2 \right)$ is positive. As a result, $\Delta E_{\mathrm{internal}}$ is negative.

Lets analyze the [[Center of Mass]] of the skater.
$$
\vec{F}_{\mathrm{ext}}=M\vec{a}_{\mathrm{cm}}
$$
To transform this to [[Work]], we multiply by $dx_{\mathrm{cm}}$:
$$
\vec{F}_{\mathrm{ext}}dx_{\mathrm{cm}}
=M\vec{a}_{\mathrm{cm}}dx_{\mathrm{cm}}
=M\frac{ dv_{\mathrm{cm}} }{ dt }v_{\mathrm{cm}}dt
=Mv_{\mathrm{cm}}dv_{\mathrm{cm}}
$$
And then to from state initial $i$ to state final $f$:
$$
\begin{align}
\int _{x_{i}}^{x_{f}} \vec{F}_{\mathrm{ext}}dx_{\mathrm{cm}}\, dx_{\mathrm{cm}}
&=\int _{v_{i}}^{v_{f}}Mv_{\mathrm{cm}} \, dv_{\mathrm{cm}} \\
&=\frac{1}{2}Mv_{\mathrm{cm, f}}^2-\frac{1}{2}Mv_{\mathrm{cm, i}}^2 \\
&=\Delta K_{\mathrm{cm}} \\
\\ \\
\Aboxed{F_{\mathrm{ext}}s_{\mathrm{cm}}&=\Delta K_{\mathrm{cm}}}
\end{align}
$$
While this is similar to the [[Work-Energy Theorem]] equation, it is not exactly it. For example, $dx_{\mathrm{cm}}$ and $s_{\mathrm{cm}}$  don't represent the displacement of the point of application of the external force (the railing).

These are also not expressions of conservation of energy: the only kind of energy that appears is translational kinetic energy. We don't include any other types of energy.

We will instead call this the Center of Mass Energy Equation.

For example, a ball rolling down an incline can be represented as:
$$
Mgs_{\mathrm{cm}}\sin\theta=\frac{1}{2}Mv_{\mathrm{cm}}^2 + \frac{1}{2} I\omega^2
$$
Using conservation of energy. However, with the Center of Mass Energy Equation:
$$
(Mg \sin\theta-f)s_{\mathrm{cm}}=\frac{1}{2}Mv^2_{\mathrm{cm}}
$$
