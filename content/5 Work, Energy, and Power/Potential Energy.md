For [[Conservative Force]]s like potential energy, the energy itself represents the state of the *system*, not an individual object. For example, a block high above the earth has a gravitational potential energy related to the block-earth system, and not the block itself. Changes in the system, like the block falling to the ground, represent a change in potential energy, or a [[Work]]:
$$
\Delta U = U_f - U_i = -W=
-\int_{s_i}^{s_f} \vec{F} \cdot d \vec{s}
$$
For a state initial $i$ and a state final $f$ that we define,

We take the inverse to find the force:
$$
\vec{F}(\vec{s})=-\frac{dU(\vec{s})}{dx}
$$
### Potential Energy of Many Particle Systems

Interpreted differently, imagine we have two particles who start separated by an infinitely large distance at rest.

Let's consider [[Gravitation]] as an example force in this scenario.

When we bring the two particles together at a constant velocity until the separation is a distance $r$ apart, we can model them as:
$$
\begin{align}
W_{\mathrm{net}}=W_{\mathrm{ext}}+W_{\mathrm{grav}}=0 \\
W_{\mathrm{grav}}=W_{\infty r}=\frac{GMm}{r}
\end{align}
$$
Where $\frac{GMm}{r}$ is the work done by gravitation. The work that we apply, $W_{\mathrm{ext}}$, is:
$$
W_{\mathrm{ext}}=-W_{\mathrm{grav}}=-\frac{GMm}{r}
$$
Which is our equation for gravitational potential energy, which we derive in [[Gravitational Potential Energy]]. We can say that:

> The potential energy of a system of particles is equal to the work done by an external agent to assemble the system, starting from the standard reference configuration.

(Physics 5th Edition, Halliday, Resnick, Krane)

In other words, potential energy can be defined as the work needed to bring the [[Systems of Particles|system]] in its current configuration from a "default" configuration.

In our case, the standard reference configuration is the initial infinite separation.

This holds for a system containing more than two particles. We can calculative potential energy
## Conservation of Mechanical Energy

For an isolated system for only conservative forces:
$$
\Delta K_{\mathrm{total}} + \Delta U_{\mathrm{total}} = 0
$$
In other words:
$$
E_{\mathrm{total}}=K_{\mathrm{total}}+U_{\mathrm{total}}
$$
> In an isolated system in which only conservative forces act, the total mechanical energy remains constant.

Using this along with the Work-Energy Theorem, we can use this to analyze conservative systems where we usually used Newton's Laws. In a more applicable form:
$$
K_i + U_i = K_f + U_f
$$
For instances with rotation, we can separate kinetic into and translational and  rotational kinetic energy:
$$
0 = K + K_{\mathrm{rotational}}+ U
$$

> At an equilibrium point of a system we consider that if we place the object (or in general the objects) there with zero Kinetic energy ,the object will stay there . The fact that the object stays there means that it will not change its position , thus **the Potential energy will remain the same** .

Using $\vec{s}(t)$ we can know the future behavior of the particle. We can find $\vec{s}(t)$ using energy:
$$
\begin{align*}
\frac{d\vec{s}}{dt} &= v\\
d\vec{s} &= v\ dt\\
\vec{s}(t)&=\int v \ dt \\
\\
\frac{1}{2}mv^2&=E-U(\vec{s})\\
v&=\sqrt{\pm(2/m)[E-U(\vec{s})]}\\
\\
\vec{s}(t)&=\int\sqrt{\pm(2/m)[E-U(\vec{s})]}\ dt
\end{align*}
$$
- - -
An important concept to know is [[Static Equilibrium; Elasticity and Fracture|Equillibrium]], a state where when you change the position of the particle the change potential energy remains at zero.
$$
\frac{dU}{d\vec{s}}=0
$$
> At an equilibrium point of a system we consider that if we place the object (or in general the objects) there with zero Kinetic energy, the object will stay there. The fact that the object stays there means that it will not change its position, thus **the Potential energy will remain the same**.
