## Deriving the Equation

Since [[Forces on Moving Charges in Magnetic Fields|Charge in a Magnetic Field Experiences a force]] $\vec{F}_{B}=q\vec{v}\times \vec{B}$, we can use this on the moving charges ([[Current]]) in a wire.

Let's derive the equation for the force on a wire.

First, we need a measure for the amount of charge. We say:
$$
\Delta Q=nA\,\Delta x\,q
$$
Where:
- $n$ is the number of charge carriers per volume.
- $A$ is the cross sectional area of the wire.
- $\Delta x$ is a certain length of the wire.
- $q$ is the charge per carrier $=1.6 \times 10^{-19} \mathrm{C}$

Then we use a couple of different equations:
$$
\begin{align}
\vec{F}_{B}&=q\vec{v} \times \vec{B} \\
&=nq\,\Delta xA\vec{v} \times \vec{B} \\
 \\
I&=\frac{ dQ }{ dt }  \\
&=nqA\frac{\Delta x}{dt} \\
&=nqA\vec{v}_{D} \\
 \\
d\vec{F}_{B}&=I \,dx \times \vec{B} \\
\Aboxed{ \vec{F}_{B}&=\int_{a}^b I  \, dx \times \vec{B} }
\end{align}
$$
Which gives us an equation for force from $a$ to $b$. We can use the [[Right-hand Rule]] to figure out the direction of the force from the [[Cross Product]]. For a straight wire, $x$ is constant, so we just use:
$$
\vec{F}_{B}=ILB
$$
## Torque on Looped Wire

For a looped wire configured as below, there will be magnetic forces outwards from each wire. You can check this using the Right–Hand Rule.

![[Pasted image 20240501234521.png]]

For an axis moving along the direction of the first part of the wire, we can calculate the [[Torque]]:
$$
\begin{align}
\Delta\tau &= \Sigma F \times r \\
&= F_{\mathrm{left}} + F_{\mathrm{right}} \\
&=(IhB)r + (-IhB)(-r) \\
&=\boxed{2IlBr}
\end{align}
$$
Giving us an equation for the torque on a wire in a magnetic field.

## Magnetic Field around a long current-carrying wire

We can use [[Ampere’s Law]] to find this equation:

![[Ampere’s Law#Along a AP Physics C — Magnetism and Current-Carrying Wires Magnetic Field around a long current-carrying wire Long Straight Current Carrying Wire|Ampere's Law]]

How can we calculate the magnetic field from multiple wires at a point $P$?
1. Calculate each wire's magnetic field $B$ on $P$.
2. Use the [[Right-hand Rule for Rotation]] to determine the direction of $B$ on $P$. (Excuse my poorly drawn hand)
![[Pasted image 20240502141215.png]]

3. "add" the vector quantities and calculate the final magnitude and direction.

For example

![[Pasted image 20240502142140.png|400]]

>[!answer]-
>![[Pasted image 20240502142535.png]]
>$$\begin{align}B&=\frac{\mu_{0}I_{1}}{2\pi 2r}\frac{\mu_{0}2I_{1}}{2\pi r}+\frac{\mu_{0}3I_{1}}{2\pi r} \\&=\left( \frac{1}{4} -1-\frac{3}{2}\right)\frac{\mu_{0}I_{1}}{\pi r} \\ &=\frac{9\mu_{0}I_{1}}{4\pi r}\end{align}$$

## For the *magnetic force* from two parallel current carrying wires:

![[Pasted image 20240502143926.png]]

We use the rotational right hand rule and reason the magnetic field of each wire on the other:
![[Pasted image 20240502190124.png]]
We then use the regular [[Right-hand Rule]] to [[Forces on Moving Charges in Magnetic Fields|reason the Magnetic Force]]:

![[Pasted image 20240502190625.png]]

Then we calculate:
$$
\begin{align}
B_{1}&=\frac{\mu_{0}I_{1}}{2\pi r} \\
F_{2}&=I_{2}lB_{1} \\
&=\frac{\mu_{0}lI_{1}I_{2}}{2\pi r} \\
F_{1}&=-\frac{\mu_{0}lI_{1}I_{2}}{2\pi r}
\end{align}
$$
It makes sense that the magnetic forces of two wires on each other equal one another because of [[Newton's Third Law]]: that every action has an equal an opposite reaction.

If the currents are moving in opposite directions:

![[Pasted image 20240502191424.png]]

Then we use the same process:

![[Pasted image 20240502191856.png]]

The force is the same:
$$
F_{2}=-\frac{\mu_{0}lI_{1}I_{2}}{2\pi r}
$$
This equation is also seen as the force per unit length:
$$
\frac{F}{l}=\frac{\mu_{0}I_{1}I_{2}}{2\pi r}
$$
Wire attract when current is in the same direction and repel when they are in opposite directions.