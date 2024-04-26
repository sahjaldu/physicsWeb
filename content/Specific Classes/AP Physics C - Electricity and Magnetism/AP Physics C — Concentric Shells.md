![[Pasted image 20240425000717.png]]

Find the [[Electric Field]] $\vec{E}$ and [[Electric Potential Difference]] $V(r)$ for:
- $r>3R$
- $2R<r<3R$
- $R<r<2R$
- $r<R$

## $R > 3R$

All the electric field lines will be pointing outwards. This is just the total charge of the whole shape.
$$
E=k \frac{Q+q}{r^2}
$$
for difference:
$$
\begin{align}
E&=k \frac{Q+q}{r} \\
V(r)&=-\int_{\infty}^r E\, dr \\
&=-k(Q+q)\int_{\infty}^r \frac{1}{r^2}\, dr \\
&=-k(Q+q) \cdot -\left( \frac{1}{x} - \frac{1}{\infty}\right) \\
v(r)&= k \frac{Q + q}{r}
\end{align}
$$

## $2R < r < 3R$

The electric field inside a conductor is zero, since all the charge goes to the surface.
$$
E=0
$$
for difference:
$$
\begin{align}
V(r)&=-\left( \int_{\infty}^{3R} E \, dr + \int_{3R}^r E \, dr  \right) \\
&=k \frac{Q + q}{3R} + 0
\end{align}
$$
The electric difference inside the conductor is equal to the difference on its surface. This is because there is no electric field inside the conductor, so it takes the same amount of work to bring a particle from infinity to the surface as infinity to any point in the conductor.

## $R < r < 2R$

The only charge enclosed is $Q$.
$$
E=\frac{kQ}{r}
$$
for difference:
$$
\begin{align}
v(r)&=-\left( \int_{\infty}^{2R} E \, dr  + \int_{2R}^r E \, dr \right) \\
&=k \frac{Q + q}{3R} + kQ \left( \frac{1}{r} - \frac{1}{2R} \right)
\end{align}
$$

## $r < R$

This much is obvious.

$$
E = \frac{kq}{r^2}
$$
and:
$$
V(r)=\frac{kq}{r}
$$

