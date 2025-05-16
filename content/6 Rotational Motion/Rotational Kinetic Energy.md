First we can look at [[Kinetic Energy]] in Polar Coordinates (See [[Rotational Motion]])
$$
K = \frac{1}{2}mv^{2}  = \frac{1}{2} m(\vec{v} \cdot  \vec{v})
$$
If $\vec{v}=v_{r}\,\hat{r} + v_{\theta}\,\hat{\theta}$, then $\vec{v} \cdot \vec{v}=v_{r}^{2}+v_{\theta}^{2}$
$$
\begin{align}
K & = \frac{1}{2}m(v_{r}^{2} + v_{\theta}^{2}) \\
 & = \frac{1}{2}m \left[ \left( \frac{ dr }{ dt }  \right)^{2} + (r\omega)^{2} \right] \\
 & = \frac{1}{2}m \left( \frac{ dr }{ dt }  \right)^{2} + \frac{1}{2}m r^{2}\omega^{2} 
\end{align}
$$
Notice that $mr^{2}$ is the [[Moment of Inertia]] $I$. So
$$
\boxed{ K = \frac{1}{2}m\left( \frac{ dr }{ dt }  \right)^{2} + \frac{1}{2}I\omega^{2} }
$$
In the case where radius is constant, we have just $\displaystyle K = \frac{1}{2}I\omega^{2}$. We can actually find this from regular Kinetic Energy.
$$
\begin{align}
K&=\frac{1}{2}mv^2 \\
&=\frac{1}{2}mr^2\omega^2 \\
&=\frac{1}{2}I\omega^2
\end{align}
$$
Kinetic Energy is additive, meaning that
$$
K_\text{tot} = \sum_{i=0}^{N} K_{i} = K_{0}+K_{1}+K_{2}+\dots K_{N}
$$
So in a situation such as a ball rolling down a hill, all we have to do is add the kinetic energies of each part of the problem. Since the ball has constant radius, the rotational portion is simply $\displaystyle K_\text{rot} = \frac{1}{2}I\omega^{2}$. The other portion is translational using the center of mass (see [[Systems of Particles]]).
$$
K_\text{tot} = \frac{1}{2}I\omega^{2} + \frac{1}{2} m_\text{cm}v^{2}
$$
