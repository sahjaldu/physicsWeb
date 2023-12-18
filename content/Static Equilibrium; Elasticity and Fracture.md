An object at rest is at **Equilibrium**.

**Statics** is the subject that determines the forces within a structure.

For an object to be in equilibrium, all forces on it must be zero, and all torques on in must be zero. In 2D:
$$
\Sigma F_{x} \qquad \Sigma F_{y}=0 \qquad \Sigma \tau=0
$$
An object in static equilibrium is either:
- Stable — after slight displacement object returns to original position. i.e. pendulum
- Unstable — after slight displacement, object moves from original position. i.e. balancing object.
- Neutral Equilibrium — after slight displacement, object is at rest. i.e. box on the floor.

We typically want stable equilibrium. To do that, the center of gravity should typically be underneath its point of support.

[[Hooke's Law]]

**Hooke's Law** says that the change in length of an object is proportional to the applied force:
$$
F=k\Delta l
$$
If the force is too great, the object will exceed its Elastic Limit, meaning that it cannot return to its original shape. When the Ultimate Strength of the material is exceeded, the object will fracture.

[[Stress]] is the force per unit area, and the resulting fractional change in length is [[Strain]].

Stress can be in three types:
- [[Compression]]
- [[Tension]]
- [[Shear]]

The ratio of Stress to Strain the called the [[Elastic Modulus]] of the material.

For the different types of stress, we use:
- Compression & Tension — Young's Modulus
- Shear — Shear Modulus

If there is a pressure from all sides, use Bulk Modulus.

To calculate change in length:
$$
\Delta l=\frac{1}{E} \frac{F}{A} l_{0}
$$
Where $E$ in whichever modulus we are using. This can be rewritten using stress and strain:
$$
\begin{align*}
\frac{\Delta l}{l_{0}}E=\frac{F}{A} \\
E=\frac{F / A}{\Delta l / l_{0}} \\
E=\frac{\mathrm{stress}}{\mathrm{strain}}
\end{align*}
$$
to calculate our Elastic Modulus.

For Shear strain, we use a similar equation with variables that are reinterpreted:
$$
\Delta l=\frac{1}{G} \frac{F}{A} l_{0}
$$

For Bulk Modulus, it isn't the length that is changing but the volume. Our stress becomes [[Pressure]] and our strain becomes a change in volume. Our equation:
$$
\begin{align*}
\frac{\Delta V}{V_{0}}=-\frac{1}{B}\Delta P \\
B=- \frac{\Delta P}{\Delta V / V}
\end{align*}
$$
