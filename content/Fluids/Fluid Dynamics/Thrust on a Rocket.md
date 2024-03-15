Using [[Bernoulli's Equation]], we can compute the thrust on a rocket.

Consider a chamber of cross-sectional area $A$ filled with a gas of density $\rho$. There is a small hole at the bottom with cross sectional area $A_{0}$. We want to find the speed at which the gas leaves the chamber, $v_{0}$.

Let us rewrite Bernoulli's Equation accordingly:
$$
p-p_{0}=\rho g(p_{0}-y) + \frac{1}{2}\rho(v_{0}^2-v^2)
$$
Where $p$ is the pressure inside the chamber and $p_{0}$ is the atmospheric pressure just outside the chamber.

For a gas, the density is usually so small we can neglect variation in pressure due to height. Removing that gives us:
$$
p-p_{0}=\frac{1}{2}\rho(v_{0}^2-v^2)
$$
Rearranged for $v_{0}$ we get:
$$
v_{0}^2=\frac{2(p-p_{0})}{\rho}+v^2
$$
We will assume [[Equations of Continuity#^6de4cc|Continuity of mass flow]] so that:
$$
Av=A_{0}v_{0}
$$
If the hole is so small that $A_{0}$ is much much smaller than $A$, then that means $v_{0}$ is much much larger than $v$. We can neglect $v^2$ in the equation. Thus, $v_{0}$ is:
$$
v_{0}=\sqrt{ \frac{2(p-p_{0})}{\rho} }
$$
If the chamber is the exhaust change of a rocket, the [[Systems of Variable Mass|thrust on the rocket]] is $v_{0} \frac{ dM }{ dt }$. In a period of time $dt$, the change in mass $dM = \rho A_{0}v_{0}dt$.
$$
v_{0} \frac{ dM }{ dt } =v_{0}(\rho A_{0}v_{0})=\rho A_{0}v_{0}^2
$$
Using our original equation:
$$
\begin{align}
v_{0}^2 \frac{ dM }{ dt } &=\frac{2(p-p_{0})}{\rho} \rho A_{0}v_{0}^2 \\
\Aboxed{v_{0}\frac{ dM }{ dt } &= 2A_{0}(p - p_{0})}
\end{align}
$$
