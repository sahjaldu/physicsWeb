Capacitance (measure in $F$ Farads) is the ability for a [[Capacitors|Capacitor]] for it to hold charge per [[Electric Potential Difference|work needed to bring the charge there]]:
$$
C=\frac{Q}{V}
$$
This definition applies when $A\gg d$. It can also be defined using [[Gauss's Law]]. For a parallel plate capacitor:
$$
\begin{align}
\oint \vec{E} \cdot d \vec{A} &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E(A)&=\frac{Q}{\epsilon_{0}} \\
E&=\frac{Q}{\epsilon_{0}A} \\
V&=-\int _{d}^0 E\, ds \\
&=-\int _{d}^0 \frac{Q}{\epsilon_{0}A}\, ds \\ \\
&=\left. -\frac{Q}{\epsilon_{0}A}s \right|_{d}^0 \\
V&=\frac{Qd}{\epsilon_{0}A} \\
C&=\frac{Q}{V} \\
&=Q \frac{\epsilon_{0} A}{Qd} \\
&=\boxed{ \frac{\epsilon_{0}A}{d} }
\end{align}
$$
When the area of the two plates are different, we only use the overlapped area.

For a Coaxial Cylinder on inner radius $a$, outer radius $b$ and length $L$, we can employ a similar process using a gaussian surface of radius $r$:
$$
\begin{align}
\oint\vec{E} \cdot d\vec{A} &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E(2\pi rL)&=\frac{Q}{\epsilon_{0}} \\
E&=\frac{Q}{2\pi rL\epsilon_{0}} \\
V&=-\int_{a}^b \vec{E} \, dr \\
&=-\int_{a}^b \frac{Q}{2\pi rL\epsilon_{0}} \, dr \\
&=\left. -\frac{Q}{2\pi L\epsilon_{0}}\ln (r) \right|_{a}^b \\
&=-\frac{Q}{2\pi L\epsilon_{0}}\ln\left( \frac{b}{a} \right) \\
C&=\frac{Q}{V} \\
&=Q \cdot- \frac{2\pi L\epsilon_{0}}{Q\ln \left( \frac{b}{a} \right)} \\
&=\boxed{ -\frac{2\pi L\epsilon_{0}}{\ln \left( \frac{b}{a} \right)} }
\end{align}
$$
For a concentric sphere capacitor with inner radius $a$ and outer radius $b$, we construct a spherical gaussian surface of radius $r$:

$$
\begin{align}
\oint\vec{E} \cdot d \vec{A} &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E(4\pi r^2)&=\frac{Q}{\epsilon_{0}} \\
E&=\frac{Q}{4\pi\epsilon_{0}r^2} \\
V&=-\int_{a}^b \vec{E} \, dr \\
&=-\int_{a}^b \frac{Q}{4\pi\epsilon_{0}r^2} \, dr \\
&=-\frac{Q}{4\pi\epsilon_{0}} \cdot -\left( \frac{1}{b}-\frac{1}{a} \right) \\
&=\frac{Q}{4\pi\epsilon_{0}}\left( \frac{1}{b}-\frac{1}{a} \right)  \\
C&=\frac{Q}{V} \\
&=Q \frac{4\pi\epsilon_{0}}{Q}\left( \frac{1}{\frac{1}{b}-\frac{1}{a}} \right) \\
&=\boxed{ 4\pi\epsilon_{0}\left( \frac{1}{\frac{1}{b}-\frac{1}{a}} \right) }
\end{align}
$$
In all of these formulas for $C$, we use $\epsilon_{0}$ for vacuum permittivity. When there is another medium, such as a [[Dielectrics|Dielectric]], we instead use $\epsilon_{0}$ with a dielectric constant $\kappa$.
$$
C=\frac{\kappa\epsilon_{0}A}{d}
$$

The [[Work]] done at any instant by a parallel plate capacitor on a charge $dq$ by a potential difference $V$ is:
$$
\begin{align}
dW&=dU=V\,dq \\
U_{E}&=\int _{0}^Q V \, dq  \\
&=\int _{0}^Q \frac{q}{C} \, dq \\
&=\frac{1}{2C}(Q^2-0^2) \\
&=\frac{Q^2}{2C} \\
&=\frac{1}{2}QV^2
\end{align}
$$

In other words, the [[Potential Energy]] stored in a Capacitor is:
$$
U=\frac{1}{2}CV^2=\frac{1}{2} \frac{Q^2}{C}=\frac{1}{2}QV
$$
We can also find the Energy Density in the [[Electric Field]] between the Plates:
$$
\begin{align}
C_{0}&=\frac{\epsilon_{0}A}{d} \\
 \\
E_{x}&=-\frac{dV}{dx} \\
\left| E \right|&=\frac{\Delta V}{d}  \\
\Delta V&=Ed \\
 \\
U_{c}&=\frac{C(\Delta V)^2}{2} \\
&=\frac{\epsilon_{0}A(\Delta V)^2}{2d} \\
&=\frac{\epsilon_{0}AE^2d^2}{2d} \\
&=\frac{\epsilon_{0}E^2Ad}{2} \\
E^2&=\frac{2}{\epsilon_{0}Ad}U_{E}
\end{align}
$$
In General:
$$
u_{e}\propto E^2
$$
