## Magnetic Force Equation

Ferromagnetic materials and particles experience a force when placed in a [[The Magnetic Field|Magnetic Field]]. For an non-magnetic object to experience force from an existing magnetic material, it must:
- Have net electric charge
- Be moving
- The direction of movement cannot be parallel to the direction of the magnetic field

The magnitude of the magnetic force can be calculated using:
$$
\vec{F}_{B}=q\vec{v} \times \vec{B}
$$
- $\vec{F}_{B}$ is the direction of the force from the magnetic field
- $\vec{v}$ is the velocity of the positive moving charge. (for negative, use the left hand, or just have the force going the opposite direction.)
- $\vec{B}$ is direction of the magnetic field.

Note that this definition uses the [[Cross Product]] and therefore [[Right-hand Rule]]. ^64483d

In this case:

![[Pasted image 20240501164729.png]]

Please excuse my poorly traced hand.

An example of using this rule:

>[!question]
> For a positive charge, which direction is the force from magnetic field?
> ![[Pasted image 20240501165036.png]]

Note that in this question, the dot represents a vector out of the page. Also, an "x" represents a vector into the page.

>[!Answer]-
>The force is upwards for a positive charge.
>

## Circular Motion

For a charged particle moving perpendicular to a magnetic field, the particle will move in a circle:

We can see this using the acceleration:
$$
a=\frac{v_{f}-v_{0}}{\Delta t}
$$
And by rearranging vectors to find acceleration, we can see how it points towards the center or a circle:
![[Pasted image 20240501172932.png]]

More clearly shown here:

![[Pasted image 20240501173239.png]]

The acceleration, which changes direction but not magnitude keeps the particle in a circular path. $\vec{F}_{B}$ is a [[Centripetal Force]] and $\vec{a}$ is a [[Centripetal Acceleration]] in this case.

Note that the direction of the magnetic field is out of the page.

We can set the equations for magnetic force and centripetal force equal in this case. (Since $\vec{B}$ and $\vec{v}$ are perpendicular, $\vec{F}_{B}=qvB$)
$$
\begin{align}
qvB&=ma_{c} \\
qvB&=\frac{mv^2}{r} \\
r &= \frac{mv}{qB}
\end{align}
$$
Giving us an equation the radius of a charged particle with the magnetic force as the centripetal force.

>[!info]
>The magnetic force never does [[Work]] on a charged particle.
>1. Force is perpendicular to displacement
>2. $W = \int F \cdot \, dx$
>3. Because of the dot product, there is no work if the force and displacement are perpendicular.

Here is an example of these concepts in use: [[AP Physics C — Mass Spectrometer Question]].
