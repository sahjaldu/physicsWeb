A Coaxial Cable is a cord that has an inner and outer conductor separated by an insulating medium. The conductors carry current in opposite directions. 
![[Pasted image 20240502194656.png]]

For the coaxial cable with inner conductor radius $a$ and current $I$, conductor radius $b$, and outer conductor radius $c$ and current $I$:

What is the magnitude of the magnetic field at a distance $r$ from the axis of the cable when $0<r<a$, when $a < r < b$, and when $r = 2c$?

When $0 < r < a$:
$$
\begin{align}
\oint \vec{B} \cdot d \vec{l} &= \mu_{0} I_{\mathrm{enc}} \\
J &= \frac{I}{\pi a^2} \\
I_{\mathrm{enc}}&=JA_{\mathrm{enc}} \\
&=\frac{Ir^2}{a^2} \\
B(2\pi r)&= \frac{\mu_{0}Ir^2}{a^2} \\
\Aboxed{ B&=\frac{\mu_{0}Ir}{2\pi a^2} }
\end{align}
$$


When $a<r<b$:
$$
\begin{align}
\oint \vec{B} \cdot d \vec{l} &= \mu_{0} I_{\mathrm{enc}} \\
B(2\pi r)&=m_{0}I \\
\Aboxed{ B&=\frac{\mu_{0}I}{2\pi r} }
\end{align}
$$
When $r=2c$:
$$
\begin{align}
\oint \vec{B} \cdot d\vec{l} &= \mu_{0} I_{\mathrm{enc}} \\
\vec{B}(2\pi r)&=\mu_{0} 0 \\
\Aboxed{ B&=0 }
\end{align}
$$
The current from both conductors cancel out since they move in opposite directions.