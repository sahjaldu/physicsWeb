Purely rotational motion means that all points are moving in a circle about an axis of rotation.

The angular position of a rotating object is specified with $\theta$. This can be defined by the length of circumference moved by the radius of the circle:
$$
\theta=\frac{l}{r}
$$
If $l=r$, then $\theta=$ 1 rad. This means that $l=r\theta$.

The angular velocity is defined the same way linear velocity is:
$$
\bar{\omega}=\frac{\Delta\theta}{\Delta t}
$$
Or with a derivative for instant angular velocity. This is usually in rads/s.

Similarly, for angular acceleration:
$$
\bar{\alpha}=\frac{\Delta\bar{\omega}}{\Delta t}
$$
We can translate both of these to linear using:
$$
\begin{align}
v&=r\omega \\
a&=r\alpha \\
\end{align}
$$
because:
$$
\begin{align}
v&=\frac{\Delta l}{\Delta t}=r\frac{\Delta\theta}{\Delta t}=r\omega \\
 \\
v&=\frac{\Delta v}{\Delta t}=r\frac{\Delta\omega}{\Delta t}=r\alpha
\end{align}
$$
For both $\omega$ and $\alpha$, the magnitude may stay the same, but the direction will always be changing.

A spinning object also has a [[Centripetal Acceleration]] that points towards the axis, $a_R$. We can rewrite this in terms of $\omega$.
$$
a_{R}=\frac{v^2}{r}=\frac{(r\omega)^2}{r}=\omega^2r
$$
Because Centripetal Acceleration and our tangential acceleration are perpendicular, we can use them as components of linear acceleration:
$$
a=\sqrt{ a_{\tan}^2 + a^2_{R}}
$$
We can also find $\theta$ using these two values. We can form a triangle:

![[Drawing 2023-12-05 21.21.38.excalidraw]]

$$
\theta=\tan^{-1}\left( \frac{a_{\tan}}{a_{R}} \right)
$$
Angular quantities are vectors, and to define their direction, we use the [[Right-hand Rule]].

[[Right-hand Rule for Rotation]]

We can relate the frequency as angular velocity over distance:
$$
\begin{align}
f=\frac{\omega}{2\pi} \\
 \\
\omega=2\pi f
\end{align}
$$
Here are the angular [[Kinematic Equations]].

[[Torque]] is a Force about an axis.

[[Rotational Inertia or Moment of Inertia]] is the rotation equivalent of mass.

[[Rotational Kinetic Energy]]

[[Angular Momentum]]

[[Angular Momentum and Angular Velocity]]

[[Precession]]

[[Rotational Kinetic Energy]]