[[Gauss's Law]] used for multiple different charged objects. For each, we construct gaussian surfaces with different radiuses $r$ or other properties.

For conductors, all the charge is at the surface. When our gaussian surface is within the object, $E=0$.

We also employ the use of different charge densities:
- linear charge density $\lambda=\frac{Q}{L}$
- surface charge density $\sigma =\frac{Q}{A}$
- volume charge density $\rho =\frac{Q}{V}$
## Conductive Spherical Symmetry

Construct a spherical gaussian surface with radius $r$ for a charged sphere with radius $R$.

When $r > R$:
$$
\begin{align}
\oint E\cdot dA &=\frac{q_{\text{enc}}}{\epsilon_{0}} \\
E( 4\pi r^2)&=\frac{q_{\text{enc}}}{\epsilon_{0}} \\
E&=\frac{1}{4\pi r^2} \frac{1}{\epsilon_{0}} \\
&=\boxed{\frac{kq}{r^2}}
\end{align}
$$


## Conductive Cylindrical Symmetry

We construct a cylindrical gaussian surface with radius $r$ and length $l$ to enclose our charged cylinder.

When $r>R$:
$$
\begin{align}
\oint E \cdot dA &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E ( 2\pi rl )&= \frac{\lambda l}{\epsilon_{0}} \\
E&= \frac{1}{2\pi\epsilon_{0}} \frac{1}{r} \\
&=\boxed{\frac{2k}{r}}
\end{align}
$$


## Conductive Planar Symmetry

We construct a box gaussian surface of height $d$, where the top and bottom sides of the box are $d/2$ away from the charged plane.

When $d < l$
$$
\begin{align}
\oint E \cdot dA &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E (A) &= \frac{\sigma A}{\epsilon_{0}} \\
E &= \boxed{ \frac{\sigma}{\epsilon_{0}} }
\end{align}
$$

## Nonconductive Spherical Symmetry

Since there is also charge within the object, not just on its surface, when $r < R$ our gaussian surface will still enclose charge.

We need to use volume charge density $\rho = Q / V$. In this case, $\rho=Q / \frac{4}{3}\pi R^2$

When $r<R$
$$
\begin{align}
\oint E \cdot dA &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E (4\pi r^2) &= \frac{\rho V_{\text{enc}}}{\epsilon_{0}} \\
&=
\frac{\rho}{\epsilon_{0}} \left( \frac{4}{3} \pi r^3\right) \\
E&=\frac{\rho}{4\pi r^2\epsilon_{0}} \left( \frac{4}{3} \pi r^3\right) \\
&=\frac{\rho r}{3\epsilon_{0}} \\
&=\frac{r}{3\epsilon_{0}}\left( \frac{Q}{\frac{4}{3} \pi R^3} \right) \\
&=\boxed{ \frac{Qr}{4\pi\epsilon_{0}R^3} }
\end{align}
$$

## Nonconductive Cylindrical Symmetry

Just like before, since there is also charge within the object, not just on its surface, when $r < R$ our gaussian surface will still enclose charge.

We still need to use volume charge density $\rho = Q / V$. In this case, $\rho=Q / \pi R^2l$.

When $r < R$:
$$
\begin{align}
\oint E \cdot dA &= \frac{q_{\text{enc}}}{\epsilon_{0}} \\
E(2\pi rl)&=\frac{\rho V_{\text{enc}}}{\epsilon_{0}} \\
&=\frac{\rho}{\epsilon_{0}}(\pi r^2l) \\
E&=\frac{\rho}{2\pi rl\,\epsilon_{0}}(\pi r^2l) \\
&=\frac{\rho r}{2\epsilon_{0}} \\
&=\frac{r}{2\epsilon_{0}}\left( \frac{Q}{\pi R^2l} \right) \\
&=\boxed{\frac{Qr}{2\pi R^2l\epsilon_{0}}}
\end{align}
$$
