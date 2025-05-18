If we have a distributed charge on some object, the principle for calculating values such as Coulomb Force, Electric Field, etc. related to the object is to first split up the object into portions, then find the value from each of those portions.

If we have some object and we want to find the Coulomb force on point outside the object, then we can break the object into pieces and calculate from each the charge $\Delta q_{i}$ of the object.
$$
\vec{F} = \frac{1}{4\pi\varepsilon_{0}} \frac{q_{1}q_{2}}{r^{2}}\hat{r} \implies \vec{F} \approx \frac{1}{4\pi\varepsilon_{0}} q_{1} \sum_{i} \frac{\Delta q_{i}}{r_{i}^{2}} \hat{r}_{i}
$$
By splitting into an infinite amount of portions, we can arrive at
$$
\lim_{ i \to \infty } \vec{F} = \lim_{ i \to \infty } \frac{q_{1}}{4\pi\varepsilon_{0}} \sum_{i} \frac{\Delta q_{i}}{r_{i}^{2}} \hat{r}_{i} \implies \frac{q_{1}}{4\pi\varepsilon_{0}} \int \frac{dq}{r^{2}}\hat{r}
$$
In order to calculate the total charge, we need to charge density function $\rho(\vec{r})$ All it does is tell us how charges are distributed over space. We often use different notations for different types of densities.
- Volume Density $\rho(\vec{r})$. $dq = \rho(\vec{r})\,dV$.
- Surface Density $\sigma(\vec{r})$. $dq = \sigma(\vec{r})\,dA$
- Line Density $\lambda(\vec{r})$. $dq = \lambda(\vec{r})\,ds$.

It is from here that we can integrate over the entire object.
$$
\vec{F} = \frac{q_{1}}{4\pi\varepsilon_{0}} \int \frac{\rho(\vec{r})\,dV}{r^{2}}\hat{r}
$$
For example, take a wire of charge of length $L$ and charge $Q$ distributed according to function $\lambda=\alpha\left( 1- \frac{x}{L} \right)$ where $\alpha$ is a known constant. How can we find the Coulomb Force at some point $\left( H, \frac{L}{2} \right)$ with charge $q$ away from the wire?

![[Pasted image 20250517220010.png]]

We impose a coordinate system on the object and integrate from $x=0$ to $x=L$.
$$
\vec{F} = \frac{q}{4\pi\varepsilon_{0}} \int_{q_{0}}^{q_{L}} \frac{\hat{r}}{r^{2}}\,dq
$$
We will do two substitutions here.
$$
dq = \alpha \left( 1-\frac{x}{L} \right)\,dx \hspace{ 0.6in } \frac{\hat{r}}{r^{2}} = \frac{1}{r^{2}} \frac{\vec{r}}{r} = \frac{\vec{r}}{r^{3}}
$$
So our integral is
$$
\vec{F} = \frac{q}{4\pi\varepsilon_{0}} \int_{0}^{L} \frac{\vec{r}}{r^{3}} \left[ \alpha\left( 1- \frac{x}{L} \right) \right]\,dx
$$
We find $\vec{r} / r^{3}$,
$$
\begin{align}
\vec{r} & = \left( \frac{L}{2}-x \right)\hat{x} + H\hat{y} \\
r & = \sqrt{ \left( \frac{L}{2}-x \right)^{2}+ H^{2} }
\end{align} \implies \frac{\vec{r}}{r^{3}} = \frac{\left( \frac{L}{2}-x \right)\hat{x} + H\hat{y}}{\left[ \left( \frac{L}{2}-x \right)^{2}+ H^{2} \right]^{3/2} }
$$
So our integral is
$$
\boxed{ \vec{F} = \frac{q}{4\pi\varepsilon_{0}} \int_{0}^{L} \frac{\left( \frac{L}{2}-x \right)\hat{x} + H\hat{y}}{\left[ \left( \frac{L}{2}-x \right)^{2}+ H^{2} \right]^{3/2} } \left[ \alpha\left( 1- \frac{x}{L} \right) \right]\,dx }
$$
The final solution for this integral is
$$
\begin{align}
F_{x}  & = \frac{2kq\alpha}{L} \left[ \ln \left( \sqrt{ a^{2}+H^{2} }+a \right) -\ln(H)- \frac{a}{\sqrt{ a^{2}+H^{2} }} \right]  \\
F_{y} & = \frac{kq\alpha L}{2H\sqrt{ a^{2}+H^{2} }}
\end{align}
$$

