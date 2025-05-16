Kinematics describes *how* objects move, as opposed to dynamics, which describes *why* objects move (see [[Kinematics vs Dynamics]]).

## Kinematic Variables

Here are some important kinematics variables:
- Position, usually using $\vec{x}$ or $\vec{y}$. Sometimes you will see $\vec{r}$ or $\vec{s}$ as well.
- Velocity, usually using $\vec{v}$ or $\vec{u}$. Velocity is the change in position over time. We can describe it using
$$
\vec{v} = \frac{\Delta \vec{x}}{\Delta t}
$$
or using calculus,
$$
\vec{v} = \frac{ d\vec{x} }{ dt }
$$
- Acceleration, usually using $\vec{a}$. Acceleration is the change in velocity over time. We can describe it using
$$
\vec{a} = \frac{\Delta \vec{v}}{\Delta t}
$$
or using calculus,
$$
\vec{a}  = \frac{ d\vec{v} }{ dt }  = \frac{ d^{2}\vec{x} }{ dt^{2} } 
$$

## Kinematic Equations:

The main Kinematic Equations you will use when starting to learn physics are:

$$
\begin{align}
\vec{v} & = \vec{v}_{0} +\vec{a}t \\
\vec{r} & = r_{0}+ \vec{v}_{0}t + \frac{1}{2}\vec{a}t^{2}  \\
v^{2} & = v_{0}^{2} +2a x \\
\end{align}
$$
Note that these equations only apply for constant values

## Derivation of Kinematic Equations

**First Equation**
$$
\begin{aligned}
\vec{a} & = \frac{ d\vec{v} }{ dt }  \\
\int \vec{a}\,dt & = \int \frac{ d \vec{v} }{ d t } \,dt \\
\vec{a}t +C& = \vec{v}
\end{aligned}\hspace{ 0.3in } 
\begin{align}
\vec{v}(0) & = \vec{a}\cdot 0 +C = C \\
\vec{v}(t) & = \vec{a}t + \vec{v}(0) \\
\Aboxed{ \vec{v} & = \vec{a}t + \vec{v}_{0} }
\end{align}
$$
**Second Equation**
$$
\begin{aligned}
\vec{v} & = \vec{a}t + \vec{v}_{0} \\
\frac{ d \vec{r} }{ d t }  & = \vec{a}t + \vec{v}_{0} \\
\int \frac{ d \vec{r} }{ d t } \,dt & = \int \vec{a}t + \vec{v}_{0}\,dt \\
\vec{r} & = \frac{1}{2}\vec{a}t^{2} + \vec{v}_{0}t + C
\end{aligned}\hspace{ 0.3in } \begin{align}
\vec{r}(0) &  = \frac{1}{2}\vec{a}\,0 + \vec{v}_{0}\,0 + C =C \\
\vec{r}(t) & = \frac{1}{2}\vec{a}t^{2} + \vec{v}_{0}t + \vec{r}(0) \\
\Aboxed{ \vec{r} & = \frac{1}{2}\vec{a}t^{2} + \vec{v}_{0}t  + \vec{r}_{0} }
\end{align}
$$
**Third Equation**
$$
v= v_{0} + at \implies t=\frac{v-v_{0}}{a}
$$
Then plug it into our second equation.
$$
\begin{align}
x(t) & =\frac{1}{2}a\left[ \frac{v-v_{0}}{a} \right] +v(0)\left[ \frac{v-v_{0}}{a} \right] +x(0) \\
 & =\frac{1}{2a}\left[v^{2}(t)-2v(t)v(0)+v^{2}(0)\right]+\frac{1}{a}\left[v(0)v(t)-v^{2}(0)\right]+x(0) \\
 & = \frac{1}{2a}[v^{ 2 }(t)-2v(t)v(0)+v^{ 2 }(0)+2v(0)v(t)-2v^{ 2 }(0)]+x(0) \\
 & =\frac{1}{2a}[v^{ 2 }(t)-v^{ 2 }(0)]+x(0)
\end{align}
$$
From this we can get the equation:
$$
\boxed{ v^{ 2 }-v_{0}^{ 2 }=2a(x-x_{0}) }
$$

**Additionally,**
$$
\begin{aligned}
\vec{v} & = \frac{ d \vec{r} }{ d t }  \\
\int \vec{v}\,dt & = \int  \frac{ d \vec{r} }{ d t }  \,dt \\
\vec{v}t +C& = \vec{r} \\
\end{aligned}\hspace{ 0.3in } 
\begin{align}
\vec{r}(0) & = \vec{v} \cdot  0 + C =C \\
\vec{r}(t) & = \vec{v}t  +\vec{r}(0) \\
\Aboxed{ \vec{r} & = vt + r_{0} }
\end{align}
$$
Note once again that these equations only work for constant values! Otherwise it is best to use calculus to solve problems.

## Problems:

**Problem 1.** A ball is launched on the $x$ axis from $x=5\mathrm{\ m}$ with velocity $10\mathrm{\ m / s}$. There is an unknown force causing an acceleration on the ball of $-2\mathrm{\ m / s^{2}}$. Find:
1. the equation of the position of the ball over time
2. the position at 5 seconds.
3. The time such that $x=0$.

**Problem 2.** The acceleration of an unknown object is given by the equation $\displaystyle a(t)=\frac{3}{4}\alpha t^{3}$. Find the equation of the position of the ball given time $t$.


