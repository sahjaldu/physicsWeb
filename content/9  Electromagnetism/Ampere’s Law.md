>[!quote]
>Ampere's Law states that for any closed loop path, the sum of the length elements times [[The Magnetic Field]] in the direction of the length element is equal to the permeability times the electric [[Current]] enclosed in the loop.

$$
\oint \vec{B} \cdot d\vec{l} = \mu_{0}I_{\mathrm{enc}}
$$
We use imaginary Amperian loops to determine the magnetic field from a surface. It is similar to [[Gauss's Law]].

Some examples:

### Along a [[AP Physics C — Magnetism and Current-Carrying Wires#Magnetic Field around a long current-carrying wire|Long Straight Current Carrying Wire]]:

![[Pasted image 20240502131105.png]]

We form an Amperian loop (green) with radius $r$ in direction $d\vec{l}$ around the wire with radius $R$ with current $\vec{I}$. We then use Ampere's Law:
$$
\begin{align}
\oint \vec{B} \cdot d\vec{l} &= \mu_{0} I_{\mathrm{enc}} \\
B(2\pi r)&=\mu_{0} I  \\
\Aboxed{ B&= \frac{\mu_{0}I}{2\pi r} }
\end{align}
$$

### Inside a Long Straight Current Carrying Wire

This is the same as before, but this time $r < R$.

Since we aren't using the whole current $I$ and only a portion, we have to use [[Current#^8f066f|Current Density]] $J=I / A$ for $I_{\mathrm{enc}}$.
$$
\begin{align}
J&=\frac{I}{A} \\
&=\frac{I}{\pi R^2} \\
I_{\mathrm{enc}}&=JA_{\mathrm{enc}} \\
&=\frac{I}{\pi R^2}(\pi r^2) \\
&=\frac{Ir^2}{R^2}
\end{align}
$$
We use this in Ampere's Law:
$$
\begin{align}
\oint \vec{B} \cdot d \vec{l} &= \mu_{0} I_{\mathrm{enc}} \\
B(2\pi r)&=\frac{\mu_{0} Ir^2}{R^2} \\
\Aboxed{ B&=\frac{\mu_{0}Ir}{2\pi R^2} }
\end{align}
$$
