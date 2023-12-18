[[Angular Momentum]] and Angular Velocity are not always parallel, and this is evident in three-dimensional cases. Take this example:

![[Pasted image 20231212182622.png|center]]

A particle of mass $m$ is attached to a rigid massless shaft by length $r'$ and it moves at a circle with constant speed $v$.

The only force that acts on the particle is the [[Centripetal Force]] from the arm. We don't consider gravity to keep things simple.

Using [[Right-hand Rule for Rotation]] the angular velocity $\vec{\omega}$ points up parallel to the axis.

The angular momentum $\vec{l}$ of the particle is given with respect to the origin $O$. This means the radius we use is $\vec{r}$ and not $r'$.
$$
\vec{l}=\vec{r}\times \vec{p}
$$
Look at $\vec{r}$ in the picture below. We fine $\vec{l}$ using the [[Cross Product]], so $\vec{l}$ does not point in the same direction as $\vec{\omega}$.

![[Pasted image 20231212184532.png|center]]

Lets focus on the components of $\vec{l}$, specifically $l$ in the $z$ direction, $l_{z}$.
$$
l_{z}=l\sin\theta=rp\sin\theta=r(mv)\sin\theta=r(mr'\omega )\sin\theta
$$
Substituting $r'$ for $r\sin\theta$:
$$
l_{z}=mr'^2\omega
$$
$mr'^2$ is the [[Rotational Inertia or Moment of Inertia]] of the particle in respect to the $z$ axis:
$$
l_{z}=I\omega
$$
Our angular velocity only applies to the component of $l$ in the $z$ direction. We know this from our initial equation:
$$
\vec{L}=\vec{I}\times\vec{\omega} 
$$
This result also means that our $\vec{l}$ changes direction over time as the particle spins around the shaft.

The other part of $\vec{L}$ causes [[Torque due to Angular Momentum]].