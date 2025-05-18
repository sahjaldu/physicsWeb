Coulomb's Law gives the electrostatic force between two particles:
$$
\vec{F}_{21}(\vec{r}) = \frac{1}{4\pi\varepsilon_{0}} \frac{q_{1}q_{2}}{r^{2}}\hat{r}_{21}
$$
Where $\hat{r}_{21}$ is the unit vector pointing from $q_{1}$ to $q_{2}$. Since it is a unit vector, $\hat{r}_{21} = \displaystyle \frac{\vec{r}_{21}}{r_{21}}$, and $\vec{r}_{21}=\vec{r}_{2}-\vec{r}_{1}$.

We often use $k$ to denote $1 / 4\pi\varepsilon_{0}$. So,
$$
\vec{F}_{21}(\vec{r})= k \frac{q_{1}q_{2}}{r^{2}}\hat{r}_{21}
$$
$\varepsilon_{0}=9.954 \times 10^{-12}\mathrm{\ N^{-1} \frac{c^{2}}{m^{2}}}$ called the electric constant or the electric permittivity of free space.

You can check the direction of force using the [[Fundamental Law of Charges]].

In terms of [[The Electric Field]],
$$
\vec{F}_{E}=q\vec{E}
$$
Coulomb's Law is an application of [[Gauss's Law]] for force between two particles.

In electromagnetism, if you have more than one charge acting on a particle, you can just add the charges. This is not true for all forces (for example, the strong nuclear force). It is from this principle that we can perform calculus for [[Distributed Charges on Objects]].

**Example.** Find the coulomb force on $q_{0}$.
![[Coulomb's Law Example.png]]

Description: we have three point charges. $q_{0}$ is at $(-x_{0},y_{0})$, $q_{1}$ is as $(r,\theta)$ in quadrant 1, and $-q_{2}$ is at $(x_{2},-y_{2})$.

The total force on $q_{0}$ is $\vec{F}_{01}$, the force of $q_{1}$ on $q_{0}$ plus $\vec{F}_{02}$, the force of $-q_{2}$ on $q_{0}$.
$$
\begin{align}
\vec{F}_\text{tot} & = \vec{F}_{01} + \vec{F}_{02} \\
 & = k \frac{q_{0}q_{1}}{r^{2}_{01}} \hat{r}_{01}  + k \frac{q_{0}(-q_{2})}{r^{2}_{02}}\hat{r}_{02}
\end{align}
$$

We can find $\hat{r}_{01}$ and $\hat{r}_{02}$.
$$
\begin{align}
\vec{r}_{01} & = (-x_{0}-r\cos\theta)\hat{x} + (y_{0}-r\sin\theta)\hat{y} \\
r_{01} & = \sqrt{ (x_{0}+r\cos\theta)^{2} + (y_{0}-r\sin\theta)^{2} }
\end{align} \implies \hat{r}_{01} = \frac{(-x_{0}-r\cos\theta)\hat{x} + (y_{0}-r\sin\theta)\hat{y} }{\sqrt{ (x_{0}+r\cos\theta)^{2} + (y_{0}-r\sin\theta)^{2} }}
$$
$$
\begin{align}
\vec{r}_{02} & = (-x_{0}-x_{2})\hat{x} + (y_{0}-y_{2})\hat{y} \\
r_{02} & = \sqrt{ (x_{0}+x_{2})^{2} + (y_{0}-y_{2})^{2} }
\end{align} \implies \hat{r}_{02} = \frac{(-x_{0}-x_{2})\hat{x} + (y_{0}-y_{2})\hat{y}}{\sqrt{ (x_{0}+x_{2})^{2} + (y_{0}-y_{2})^{2} }}
$$
Let's rewrite our vectors to make the problem easier:
$$
\frac{\hat{r}}{r^{2}} = \frac{1}{r^{2}} \frac{\vec{r}}{r} = \frac{\vec{r}}{r^{3}}
$$
So
$$
\begin{align}
\vec{F}_{01}  & = kq_{0}q_{1} \frac{(-x_{0}-r\cos\theta)\hat{x} + (y_{0}-r\sin\theta)\hat{y}}{[(x_{0}+r\cos\theta)^{2}+(y_{0}-r\sin\theta)^{2}]^{3/2}} \\
\vec{F}_{02} & = -kq_{0}q_{2} \frac{(-x_{0}-x_{2})\hat{x} + (y_{0}-y_{2})\hat{y}}{[(x_{0}+x_{2})^{2}+(y_{0}-y_{2})]^{3/2}} \\
\vec{F}_\text{tot} & = \vec{F}_{01} + \vec{F}_{02}
\end{align}
$$
We can split this into $\hat{x}$ and $\hat{y}$ components.
$$
\begin{align}
\vec{F}_\text{tot} & = kq_{0}\left[ \left( \frac{q_{1}(-x_{0}-r\cos\theta)}{[(x_{0}+r\cos\theta)^{2} + (y_{0}-r\sin\theta)^{2}]^{3/2}} + \frac{q_{2}(x_{0}+y_{0})}{[(x_{0}+x_{2})^{2}+(y_{0}-y_{2})^{2}]^{3/2}} \right)\hat{x} \right.  \\
 & \hspace{ 0.4in } + \left. \left( \frac{q_{1}(y_{0}-r\sin\theta)}{[(x_{0}+r\cos\theta)^{2} + (y_{0}-r\sin\theta)^{2}]^{3/2} }- \frac{q_{2}(y_{0}-y_{2})\hat{y}}{[(x_{0}+x_{2})^{2}+(y_{0}-y_{2})^{2}]^{3/2}}  \right) \hat{y} \right]
\end{align}
$$
