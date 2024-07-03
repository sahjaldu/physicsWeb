Gravitational Potential Energy is the [[Potential Energy]] of a [[Systems of Particles|System]] concerning the Force of [[Gravitation]].

Close to the ground, it can be simplified to:
$$
U_{G}=mgh
$$
However, we cannot simplify this in space. We must use [[Gravitation#^d91d19|Newton's Law of Universal Gravitation]]:
$$
F_{G}=\frac{GMm}{r^2}
$$
to determine the gravitational potential energy.

For this task, we can use [[Work]], where $\Delta U=U_{b}-U_{a}=-W_{ab}$ where we get the work done as the system changes from configuration $a$ to $b$.

Remember that Potential Energy is a [[Conservative Force]], so we only care about the start and end result.

For that, we use the work in integral form:
$$
\begin{align}
W_{ab}=\int ^b_{a}\vec{F}\cdot d\vec{r}
\end{align}
$$
Because $\vec{F}$ and $\vec{r}$ point in opposite directions, we can change our [[Dot Product]] to a negative sign:
$$
W_{ab}=-\int ^b_{a} F \, dr 
$$
Continuing:
$$
\begin{align}
W_{ab}&=-\int _{\Large r_{a}}^{\Large r_{b}} \frac{GMm}{r^2} \, dr \\
&=-GMm \int _{\Large r_{a}}^{\Large r_{b}} \frac{1}{r^2} \, dr \\
&=-GMm \left. \left( -\frac{1}{r} \right)  \right|_{\Large r_{a}}^{\Large r_{b}} \\
&=GMm\left( \frac{1}{r_{b}} - \frac{1}{r_{a}} \right)   
\end{align}
$$
Our difference in potential energy is negative work, so:
$$
\Delta U=U_{b}-U_{a}=-W_{ab}=GMm\left( \frac{1}{r_{a}} - \frac{1}{r_{b}} \right)   
$$
We can consider the value of potential energy at a single point by taking an infinite separation of the particles (where the potential energy is zero).
$$
\begin{align}
U(\infty)-U(r)&=GMm\left( \frac{1}{r}-0 \right) \\
\Aboxed{U(r)&=-\frac{GMm}{r}}
\end{align}
$$
For [[Systems of Particles]] with more than two particles considered, we use a similar logic.

Take a look at the example from the [[Potential Energy]] page.

![[Potential Energy#Potential Energy of Many Particle Systems]]

Lets consider a system for three masses, $m_{1}$, $m_{2}$, $m_{3}$, which start infinitely separated from each other. To find the work needed to bring it to a set of distances from each other (detailed below) we move each particle, one by one, at a constant velocity, our external force counteracting the gravitational force.

![[Pasted image 20240104141238.png|center]]

Our potential energy is:
$$
U=-\left( \frac{Gm_{1}m_{2}}{r_{12}} + \frac{Gm_{1}m_{3}}{r_{13}} + \frac{Gm_{2}m_{3}}{r_{23}} \right) 
$$
We just combine the external work done for each particle and then use that to find gravitational potential energy, similar to before. This makes sense: potential energy is based off the configuration of the system.

If we wanted to separate our masses once again, we would apply an energy:
$$
E=+\left( \frac{Gm_{1}m_{2}}{r_{12}} + \frac{Gm_{1}m_{3}}{r_{13}} + \frac{Gm_{2}m_{3}}{r_{23}} \right) 
$$
Also known as the *binding energy*.

>[!info]
>The derivative of gravitational potential energy with respect to $r$ is $F_{g}$, shown:
>$$\begin{align}\frac{d}{dr} \frac{GMm}{r}=-\frac{GMm}{r^2}\end{align}$$
