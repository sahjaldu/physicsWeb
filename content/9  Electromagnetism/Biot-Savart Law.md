The Biot-Savart Law finds small contributions of [[The Magnetic Field]] from small contributions of length from non-linear [[Current]] carrying wires.
$$
d\vec{B} = \frac{\mu_{0}}{4\pi} \frac{I\vec{dl}\times\hat{r}}{r^2}
$$
After you have all the small contributions, you integrate both sides to find the total magnetic field.

>[!note]
>$\hat{r}$ is a [[Unit Vectors|Unit Vector]] that gives the direction of $r$.

For example, for a current carrying coil:
![[Pasted image 20240502231521.png]]

In this case $d\vec{l}$ and $\hat{r}$ are always perpendicular.

Lets plug in terms:
$$
\begin{align}
d\vec{B} &= \frac{\mu_{0} I}{4\pi} \frac{d\vec{l} \times \hat{r}}{r^2} \\
&= \frac{\mu_{0} I}{4\pi} \frac{d\vec{l}}{r^2} \\
\int  \, d\vec{B} &= \int  \frac{\mu_{0}I}{4\pi} \frac{dl}{r^2}  \\
\vec{B} &=  \frac{\mu_{0}I}{4\pi r^2} \int  \, dl  \\
&=\frac{\mu_{0}I}{4\pi r^2} 2\pi r \\
\Aboxed{ \vec{B} &=\frac{\mu_{0}I}{2r} }
\end{align}
$$
We can also use this to find the [[AP Physics C — Magnetism and Current-Carrying Wires#Magnetic Field around a long current-carrying wire|Magnetic Field on a long, straight, current-carrying wire]], and see if it is the same as when we use [[Ampere’s Law]].

![[Pasted image 20240502233307.png]]

We establish a point $P$ in which we calculate the magnetic field on. Also, we use $d\vec{l} \times \hat{r} = dl\sin\theta$.
$$
\begin{align}
\vec{B} &= \int_{-\infty}^\infty d\vec{B} \\
&=2\int_{0}^{\infty} d\vec{B} \\
&=2\int_{0}^{\infty} \frac{\mu_{0}I}{4\pi r^2} \sin\theta\, dl  \\
&=\frac{2\mu_{0}I}{4\pi}\int_{0}^{\infty} \frac{dl\,\sin\theta}{r^2} \\
  \\
\sin\theta &= \frac{R}{r} \\
r &= \frac{R}{\sin\theta} \\
r^2 &= \frac{R^2}{\sin^2\theta} \\
\tan\theta &= \frac{R}{l} \\
l&= \frac{R}{\tan \theta} \\
&=R\cot\theta \\
dl&=-R\csc^2 \theta \,d\theta \\
&= -\frac{R}{\sin^2\theta}d\theta \\
 \\
\vec{B} &=\frac{\mu_{0}I}{2\pi} \int_{0}^{\infty} -\frac{R}{\sin^2 \theta} d\theta \sin\theta \left( \frac{\sin^2\theta}{R^2} \right) \\
&=\frac{\mu_{0}I}{2\pi} \int_{0}^\infty -\frac{\sin\theta}{R} \, d\theta  \\
&=-\frac{\mu_{0}I}{2\pi R} \int_{\pi / 2}^0 \sin\theta \, d\theta \\
&=-\frac{\mu_{0}I}{2\pi R}\left[ \cos 0 - \cos(\pi / 2) \right] \\
\Aboxed{ \vec{B} &= \frac{\mu_{0}I}{2\pi R} }
\end{align}
$$
