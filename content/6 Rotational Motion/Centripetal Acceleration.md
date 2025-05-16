A spinning object has a centripetal acceleration towards its axis that keeps it spinning. Even if the speed at any time is not changing, the direction is, meaning that there is a change in velocity over time, and therefore an acceleration.

We can obtain an equation for centripetal acceleration using the equation for linear acceleration in terms of polar coordinates (see [[Rotational Motion]]).
$$
\vec{a} = \left[ \frac{ d^{2}r }{ dt^{2} }  - r\omega^{2} \right] \hat{r} + \left[ 2 \frac{ dr }{ dt } \omega + r\alpha \right]\hat{\theta}
$$
Assuming the radius is constant, we get
$$
\vec{a} = [-r\omega^{2}]\,\hat{r}  + [r\alpha]\,\hat{\theta}
$$
Since centripetal acceleration is only radial, we get
$$
\vec{a} = -r\omega^{2}\,\hat{r}
$$
Why is this negative? $\hat{r}$ is outwards, and centripetal acceleration is inwards towards the center. We can also write this as
$$
\vec{a} = -r \left( \frac{v}{r} \right)^{2}\,\hat{r} = -\frac{v^{2}}{r}\hat{r}
$$
We can also find the same result using a different method. Acceleration is defined by:
$$
\vec{a}=\frac{\vec{v}_{2}-\vec{v_{1}}}{\Delta t}=\frac{\Delta \vec{v}}{t}
$$
However, our velocity doesn't only change by magnitude, but also by direction.

Let's assume we have an acceleration of constant magnitude. By taking a very small change in $l$ along the circumference over a very small $\Delta t$, we get:
![[Pasted image 20231205192715.png]]

Our $\Delta \vec{v}$ is the difference between these two velocities, so:

![[Pasted image 20231205192803.png]]

As $\Delta\theta$ becomes increasingly smaller, $\vec{v}_{1}$ will become almost parallel to $\vec{v}_{2}$ and $\Delta \vec{v}$ will point towards the center of the circle. As a result, $\vec{a}$ will also point towards the center of the circle.

Since we are only focusing on direction and not magnitude, we will have it be different from normal angular acceleration and call it centripetal acceleration $\vec{a}_{R}$.

We can calculate the magnitude of centripetal acceleration. Take $\Delta\theta$ and $\Delta t$ to be extremely small and $v=v_{1}=v_{2}$ since the magnitude does not change (note that $v$ does not have an arrow—this is a magnitude), we can write:
$$
\begin{align}
\frac{\Delta v}{v}&\approx \frac{\Delta l}{r} \\
\Delta v&=\frac{v}{r}\Delta l \\
 \\
a_{r}&=\frac{\Delta v}{\Delta t}=\frac{v}{r} \frac{\Delta l}{\Delta t}=\frac{v}{r}v \\ \\
a_{r}&=\frac{v^2}{r} \\
\end{align}
$$
Using centripetal acceleration, we can get a [[Centripetal Force]].
