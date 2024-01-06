The law of gravitation is an [[Inverse Square Law]] meaning that it varies proportionally to a distance squared.

The force of gravity is:
$$
F=G \frac{m_1 m_2}{r^2}
$$

^8687ca

Where $G$ is the *gravitational constant*,
$$
G=6.67 \times 10^{-11} \mathrm{N \cdot m^2 / kg^2}
$$
$m_1$ and $m_2$ are the mass of two objects, and $r$ is the distance between their [[Center of Mass|centers of mass]].

In terms of [[Vectors]], our law is:
$$
\vec{F}_{12}=-G \frac{m_1 m_2}{r^2_{12}} \hat{r}_{12}
$$
and
$$
\vec{F}_{21}=-G \frac{m_1 m_2}{r^2_{21}} \hat{r}_{21}
$$
Where $\hat{r}$ is a unit vector with magnitude $1$ that only specifies the direction from the other mass to this mass. We have a negative sign because we are indicating that the force is opposite the direction from the other mass to this mass.

This is what the subscript represents.
- $F_{12}$ the force of $m_2$ on $m_1$, a vector pointing from $m_1$ to $m_2$.
- $\hat{r}_{12}$ represents the distance from $m_2$ to $m_1$, a vector pointing from $m_2$ to $m_2$.

And vice-versa for $F_{21}$ and $\hat{r}_{21}$.
![[Pasted image 20231222005612.png|center]]

Note that $\left | F_{12} \right | = \left | F_{21} \right |$. 

When there are more than two bodies, we can add vectors to find the total gravitational force for a mass.

For gravitation near the earth's surface, we often use the free-fall acceleration from gravity $g_0$. With Newton's second law:
$$
F=mg_0
$$
Many times we assume that $g_0=9.8 \ \mathrm{m / s^2}$, but acceleration due to gravity does change depending on the distance from the earth's surface. Combining the above equation with Newton's law of gravitation:
$$
g_0=\frac{GM_E}{r^2}
$$
Where $M_E$ is the mass of the earth.

There are also more irregularities:
1. The density of the earth varies from point to point
2. The earth itself is approximately an ellipsoid, not a sphere.
3. The earth is rotating, shifting those irregularities constantly and creating a centrifugal force that varies based on latitude.

It is difficult to take the mass of every particle on earth and sum the gravitational force vectors from each to find a good gravitational force. However, using the first [[The Two Shell Theorems|Shell Theorem]]:

![[The Two Shell Theorems#^c89bad]]

We can represent the earth as a point mass located at its center (Its [[Center of Mass]]).

The distance $r$ from $m_1$ to $m_2$ is from the center of each mass, not its surface.

[[Gravitational Potential Energy]]

[[Escape Speed]]

[[The Motions of Planets and Satellites]