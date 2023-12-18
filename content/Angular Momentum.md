Momentum also has a [[Rotational Motion]] analog, Angular momentum $L$:
$$
\begin{align*}
\vec{L}=\vec{I}\times\vec{\omega} \\
 \\
\vec{L}=I\omega \sin (\theta)
\end{align*}
$$
Newton's Law can be written as
$$
\begin{align*}
F&=ma \\
F&=\frac{ dp }{ dt } 
\end{align*}
$$
Similarly:
$$
\begin{align*}
\tau&=I\omega \\
\tau&=\frac{ dL }{ dt } 
\end{align*}
$$
We can derive this:
$$
\begin{align*}
\frac{ d\vec{l} }{ dt }&=\frac{d}{dt} (\vec{r}\times \vec{p})  \\
&=\frac{ d\vec{r} }{ dt } \times \vec{p}+\vec{r}\times \frac{ d\vec{p} }{ dt }  \\
&=(\vec{v}+m\vec{v})+\vec{r}\times \frac{ d\vec{p} }{ dt }  \\
\vec{v}\times m\vec{v}=0 \\
&=\vec{r}+\sum\vec{F} \\
&=\tau
\end{align*}
$$
The analogy from translational to rotational carries over in other ways.

To specify direction for $\vec{L}$, use the [[Right-hand Rule for Rotation]]. This looks like:

![[Pasted image 20231212181447.png|center]]

We can compare this to linear momentum:

![[Pasted image 20231212181531.png|center]]

Suppose we have a force $\vec{F}$ acting on a particle with momentum $\vec{p}$ which as a result changes by $\Delta p$. Lets say that $\Delta p$ is very small. 

When $\vec{F}$ is parallel with $\vec{p}$, the momentum of the particle changes to $\vec{p}+\Delta \vec{p}$. When $\vec{F}$ is perpendicular, the momentum of the particle changes to $\sqrt{ \vec{p}+\Delta \vec{p} }$, but since $\Delta \vec{p}$ is so small, the only effect is a change in direction.

![[Pasted image 20231212000918.png|center]]

A similar phenomenon occurs for rotational movement. When $\vec{\tau}$ is parallel with $\vec{L}$, the momentum of the particle changes to $\vec{L}+\Delta \vec{L}$. When $\vec{\tau}$ is perpendicular, the momentum of the particle changes to $\sqrt{ \vec{L}+\Delta \vec{L} }$, but since $\Delta \vec{L}$ is so small, the only effect is a change in direction.

Using this principle, we can show an interesting phenomena:

![[Pasted image 20231212002151.png|center]]

Because the torque of the wheel is perpendicular to the angular momentum, the axle moves.

There is also a law for Conservation of Angular Momentum where $L$ is constant. This causes many interesting phenomena to occur. For example, as $r$ decreases, $I$ decreases, meaning that $\omega$ must increase.

For Conservation of Angular Momentum to be sustained, net [[Torque]] must stay the same, but the Force does not. The object can undergo translational motion without introducing an outside torque to the object.

 [[Angular Momentum and Angular Velocity]]
 