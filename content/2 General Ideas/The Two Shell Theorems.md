Oftentimes we can use the two *shell theorems* to simply the analysis of forces following an [[Inverse Square Law]]. The shell theorems state:

**Shell Theorem 1:**

A uniformly dense spherical shell attracts an external particle as if all the mass of the shell were concentrated at its center. ^c89bad

**Shell Theorem 2:**

A uniformly dense spherical shell exerts no gravitational force on a particle located anywhere inside it.

### Proof of the Shell Theorems:

![[Pasted image 20231221203230.png|center]]

Lets use the gravitational force for this example.

We have a shell of total mass $M$, thickness $t$, and uniform density $\rho$, and a point mass $m$ at point $P$ a distance $r$ from the center of the shell.

We also have a very very thin ring of width $r\,d\theta$. Because the ring is so thin, every particle on the ring is a distance $x$ from $m$.  An example particle on the ring at point $A$ exerts a force $\vec{F}_A$ on m, and another example particle at point $B$ exerts a force $\vec{F}_B$ on $m$. Both forces have equal magnitude and their sum lies on the line $PO$, which is also true for any other two opposite particles on the ring.

For an element of mass $dm_a$ at point A, the component of force along $PO$ is:
$$
dF_A=G \frac{m\,dm_A}{x^2}\cos\alpha
$$
For extending this for every mass element in the ring:
$$
\begin{align*}
dF&=dF_A + dF_B + \dots \\
&=\frac{Gm}{x^2}\cos\alpha(dm_A+dm_B+\dots) \\
&=\frac{Gm\,dM}{x^2}\cos\alpha
\end{align*}
$$
Getting the volume from the mass, then using it to find total mass:
- The ring has dimensions $t \times R\,d\theta \times2\pi(R\sin\theta)$
- $2\pi(R\sin\theta)$ is the circumference of the ring.

$$
\begin{align*}
dM&=\rho\,dV \\
&=\rho2\pi t R^2 \sin \theta\, d \theta \\
&= \frac{M\sin\theta\,d\theta}{2}
\end{align*}
$$
Lets plug this into our equation for $dF$:
$$
dF=\frac{Gm\,dM}{x^2}\cos\alpha=\frac{GmM}{2x^2}\cos\alpha \sin\theta \, d\theta
$$
Using law of cosines for triangle $AOP$ to get an expression for $\theta$ gets us:
$$
\begin{align*}
x^2&=r^2+R^2-2rR\cos\theta \\
\cos\theta&=\frac{r^2+R^2-x^2}{2rR}
\end{align*}
$$
Which we differentiate for $\theta$ to get:
$$
\sin\theta\,d\theta=\frac{x}{rR}dx
$$
We can also take law of cosines with $\alpha$, giving us:
$$
\begin{align}
R^2&=r^2+x^2-2rx\cos\alpha \\
\cos\alpha&=\frac{r^2+x^2-R^2}{2rx}
\end{align}
$$
Substituting these into the equation for $dF$ gives us:
$$
\begin{align}
dF&=\frac{GmM}{2x^2}\cos\alpha \sin\theta \, d\theta \\
&=\frac{GmM}{2x^2} \frac{r^2+x^2-R^2}{2rx} \frac{x}{rR}dx \\
&=\frac{GmM}{4Rr^2} \frac{r^2-R^2+x^2}{x^2}\,dx
\end{align}
$$
To get the total force, take the integral:
$$
\begin{align}
F&=\frac{GmM}{4Rr^2} \int^{r+R}_{r-R} \frac{r^2-R^2+x^2}{x^2} \, dx  \\
&=\frac{GmM}{4Rr^2} 4R \\
\Aboxed{&=\frac{GmM}{r^2}}
\end{align}
$$
Where $r$ is the radius from the center of the shell, proving shell theorem 1.

When we apply the method method above for $r<R$, note that $R-r=0$.

![[Pasted image 20231221204638.png|center]]

As a result, when you take the integral from the inside of the shell, the result will be zero, proving shell theorem 2.