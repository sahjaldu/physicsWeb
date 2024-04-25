![[Pasted image 20240424163824.png]]

Find the [[Fundamental Law of Charges|Charge]], [[Electric Field]], and [[Electric Potential Difference]] a distance $R$ away from the charged Arc.

## Charge

We can use arclength $L=R\theta$ and linear charge density $\lambda=q / L$.
$$
\begin{align}
Q&=\int dq \\
dq&=\frac{Q}{L}dl \\
&=\lambda\, dl \\
&=\lambda R\,d\theta \\
Q&=\int _{-\theta}^\theta \lambda R\,d\theta \\
&=\lambda R \int _{-\theta}^\theta d\theta \\
&=\lambda R(\theta--\theta) \\
&=\boxed{2\lambda R\theta}
\end{align}
$$

## Electric Field

Since the $y$ component of the electric field cancels out, we only need to look at the $x$ component using $\cos\theta$. In this problem, we also use $dq=\lambda R\,d\theta$ found while looking for charge.
$$
\begin{align}
E&=\frac{kQ}{R^2} \\
dE&=\frac{k\,dq}{R^2} \cos\theta\\
\int dE &=\int \frac{k\,dq}{R^2}\cos\theta \\
E&=\int_{-\theta}^\theta \frac{k\lambda R\cos\theta}{R^2} \, d\theta \\
&=\frac{k\lambda}{R}\int \cos\theta \, d\theta \\
&=\frac{k\lambda}{R}\left. \sin\theta \right|^{\theta}_{-\theta} \\
&=\boxed{\frac{2k\lambda}{R}\sin\theta}
\end{align}
$$

## Electric Potential

$$
\begin{align}
V&=\frac{kQ}{R} \\
dV&=\frac{k\,dq}{R} \\
\int dV &= \int  \frac{k\lambda R\,d\theta}{R} \\
V&=k\lambda \int _{-\theta}^\theta d\theta \\
V&=\boxed{2k\lambda\theta}   
\end{align}
$$

All three solutions have to do with 
1. splitting up the curved surface into small parts
2. replacing terms with charge density and other measures of length ($l,\ \theta$).
