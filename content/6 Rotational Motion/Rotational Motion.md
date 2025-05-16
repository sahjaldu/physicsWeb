Sometimes we encounter situations where there is an object moving about an axis. The simplest method to handle these cases is to introduce a circular coordinate system

![[Rotational Motion Polar Coordinates.png]]

We turn our rectangular coordinate system using an $x$ and $y$ axis into a polar coordinate system based on radius $r$ and angle with some respect to some direction (typically the $x$-axis) $\theta$. A point $(0,2)$ in rectangular coordinates is $\left( 2, \frac{\pi}{2} \right)$ in polar coordinates. In general, polar coordinates are written $(r,\theta)$. Note that some $-r = r+\pi$ and $\theta=2\pi+\theta$. The arclength $s$ along a circle of radius $R$ is $s=R(\Delta\theta)$.

So a vector in polar coordinates will be described as $\vec{v} = a\hat{r} + b\hat{\theta}$, unlike in rectangular coordinates where vectors are described $\vec{v} = a\hat{x} + b \hat{y}$. To convert we do:
$$
\begin{align}
\hat{r} & = \cos\theta\,\hat{x} + \sin\theta\,\hat{y} \\
\hat{\theta} & = -\sin\theta\,\hat{x} + \cos\theta\,\hat{y}
\end{align}
$$
Note how $\hat{\theta}$ is the derivative of $\hat{r}$ with respect to $\theta$! Wow! Sigma!

Some variables:
$$
\begin{array}{lll}
r(t) \hspace{ 0.1in } \text{radius} &  & \displaystyle  \frac{ dr }{ dt } \hspace{ 0.1in } \text{radial velocity} &  & \displaystyle  \frac{ d^{2}r }{ dt^{2} } \hspace{ 0.1in } \text{radial acceleration} \\
\theta(t) \hspace{ 0.1in } \text{angle} &  & \displaystyle  \frac{ d \theta }{ d t } \hspace{ 0.1in } \text{angular velocity} &  & \displaystyle  \frac{ d^{2}\theta }{ dt^{2} } \hspace{ 0.1in } \text{angular acceleration}
\end{array}
$$
Angular velocity is also denoted $\omega$ and angular acceleration is also denoted $\alpha$. We can also use the following equations to equate angular acceleration and velocity to rectangular acceleration and velocity.
$$
\begin{align}
v & = r\omega \\
a & = r\alpha
\end{align}
$$
Since
$$
\begin{align}
v & = \frac{ds}{dt} = r \frac{d\theta}{dt} = r\omega \\
a & = \frac{dv}{dt} = r \frac{d\omega}{dt} = r\alpha
\end{align}
$$
This makes sense. Imagine two points on a spinning record, one closer to the center of the record and one farther. Even though entire record has the same angular velocity and acceleration, the point at the center of the record moves a smaller distance in the same amount of time as the point farther from the center. So the point closer to the center has a smaller velocity because its distance from the center is smaller.

However, this is only the case for a pure angular acceleration and velocity. If we introduce a radial velocity and acceleration, we get much more complicated equations.
$$
\boxed{ \begin{array}{c}
\displaystyle  \vec{v}  = \frac{ dr }{ dt } \hat{r} + r \omega \hat{\theta} \\
\displaystyle  \vec{a} = \left[ \frac{ d^{2}r }{ dt^{2} }  - r\omega^{2} \right] \hat{r} + \left[ 2 \frac{ dr }{ dt }   \omega + r\alpha \right]\hat{\theta}
\end{array} }
$$
The derivation is as follows. For velocity,
$$
\vec{v} = \frac{d\vec{r}}{dt} = \frac{d}{dt}  [r\,\hat{r}]  = \frac{ dr }{ dt } \hat{r} + r \frac{d}{dt} [\hat{r}]
$$
Since
$$
\begin{align}
\frac{d}{dt} [\hat{r}] & = \frac{d}{dt} [\cos\theta \,\hat{x}  + \sin\theta\,\hat{y}] \\
 & = \frac{d\theta}{dt} \frac{d}{d\theta} [\cos\theta \,\hat{x}  + \sin\theta\,\hat{y}]  \\
 & =  \frac{d\theta}{dt}(-\sin\theta \,\hat{x} + \cos\theta\,\hat{y}) \\
 & = \omega\,\hat{\theta}
\end{align}
$$
So,
$$
\boxed{ \vec{v} = \frac{ dr }{ dt } \hat{r} + r \omega\,\hat{\theta} }
$$

For acceleration,
$$
\begin{align}
\vec{a}  = \frac{d\vec{v}}{dt} &  = \frac{d}{dt} \left[ \frac{ dr }{ dt } \hat{r} + r\omega\,\hat{\theta} \right] \\
 & = \frac{d}{dt} \left[ \frac{ dr }{ dt }  \right]\hat{r} + \frac{ dr }{ dt } \frac{d}{dt} [\hat{r}] + \frac{d}{dt} [r]\,\omega\,\hat{\theta} + r \,\frac{d}{dt} [\omega]\,\hat{\theta} + r\omega\,\frac{d}{dt} [\hat{\theta}]
\end{align}
$$
Since
$$
\begin{align}
\frac{d}{dt} [\hat{\theta}] & = \frac{d}{dt} [-\sin\theta\,\hat{x} + \cos\theta\,\hat{y}] \\
 & = \frac{d\theta}{dt} \frac{d}{d\theta} [-\sin\theta\,\hat{x} + \cos\theta\,\hat{y}] \\
 & = \frac{d\theta}{dt} (-\cos\theta\,\hat{x} -\sin\theta\,\hat{y}) \\
 & = -\omega \,\hat{r}
\end{align}
$$
So,
$$
\begin{align}
\vec{a} & = \frac{d}{dt} \left[ \frac{ dr }{ dt }  \right]\hat{r} + \frac{ dr }{ dt } \omega\,\hat{\theta} + \frac{d}{dt} [r]\,\omega\,\hat{\theta} + r \,\frac{d}{dt} [\omega]\,\hat{\theta} - r\omega\omega\,\hat{r} \\
 & = \frac{ d^{2}r }{ dt^{2} } \hat{r} + \frac{ dr }{ dt } \omega\,\hat{\theta} + \frac{ dr }{ dt }\omega\,\hat{\theta} + r\alpha\,\hat{\theta} - r\omega^{2}\,\hat{r} \\
 & = \boxed{ \left[ \frac{ d^{2}r }{ dt^{2} } -r\omega^{2} \right]\hat{r} + \left[ 2\frac{ dr }{ dt } \omega + r\alpha \right]\hat{\theta} }
\end{align}
$$
Notice how in both equation, if we keep $r$ constant, we are left with
$$
\begin{align}
\vec{v} & = r\omega\,\hat{\theta} \\
\vec{a} & = [-r\omega^{2}]\hat{r} + [r\alpha]\hat{\theta}
\end{align}
$$
The radial part of the acceleration is called [[Centripetal Acceleration]].

From our equation for acceleration we can find force in polar coordinates.
$$
\vec{F} = m\vec{a} = m\left[ \frac{ d^{2}r }{ dt^{2} }  - r\omega^{2} \right]\hat{r} +m \left[ 2\frac{ dr }{ dt } \omega + r\alpha \right] \hat{\theta}
$$
[[Right-hand Rule for Rotation]]

We can relate the frequency as angular velocity over distance:
$$
\begin{align}
f=\frac{\omega}{2\pi} \\
\omega=2\pi f
\end{align}
$$
For constant and purely angular values, we can use angular Kinematic Equations:
$$
\begin{align}
\omega & = \omega_{0}+\alpha t \\
\theta & = \omega_{0}t + \frac{1}{2}\alpha t^{2} \\
\omega^{2} & = \omega_{0}^{2} +2\alpha\theta
\end{align}
$$
[[Torque]] is a Force about an axis.

[[Moment of Inertia]] is the rotation equivalent of mass.

[[Rotational Kinetic Energy]]

[[Angular Momentum]]

[[Angular Momentum and Angular Velocity]]

[[Precession]]

[[Rotational Kinetic Energy]]