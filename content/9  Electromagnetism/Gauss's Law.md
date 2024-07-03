Gauss's Law states that the net [[Electric Flux]] through any imaginary closed surface is equal to the net charge enclosed within that surface divided by $\epsilon_{0}$.
$$
\phi_{\text{net}} = \frac{q_{\text{enclosed}}}{\epsilon_{0}}
$$
We can use the [[Electric Flux]] equation to make this more useful:
$$
\phi_{E}=\oint \vec{E} \cdot \vec{dA} = \frac{q_{\text{en}}}{\epsilon_{0}}
$$
The integral here is a closed integral, which is just a notation that says that we are using a closed surface.

Note that these are *imaginary* surfaces, and are not meant to be surfaces that actually exist. By manipulating these imaginary surfaces, we can find information about electric field and charge.

We get our equation for enclosed charge over $\epsilon_{0}$ by assuming the surface shown:
![[Pasted image 20240424115556.png|500]]

Then plugging in terms for this surface into the electric flux equation, then cancelling.

$$
\begin{align}
\phi&=\oint\vec{E}\cdot \vec{dA} \\
\phi&=\vec{E}\cos \theta \oint  \vec{dA} \\
\phi&=\frac{1}{4\pi\epsilon_{0}} \frac{q}{r^2} (4\pi r^2) \\
\phi&=\frac{q}{\epsilon_{0}}
\end{align}
$$
