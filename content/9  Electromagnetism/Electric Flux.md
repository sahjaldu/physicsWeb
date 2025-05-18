Electric Flux $\phi$ is the amount of [[The Electric Field|Electric Field]] lines flowing through an area. Mathematically, this is represented as:
$$
\Phi_{E}=\vec{E}\cdot \vec{A}
$$
The area [[Vectors|Vector]] is equal to $\vec{A}=({\text{Area})}(\hat{n})$ where $\hat{n}$ is the direction of the normal vector. This is so that when the area is at an angle, we can show that the flux has diminished.

![[Pasted image 20240424112113.png]]

For example, the flux in example 1 is greater than the flux at example 2. Because we are using a [[Dot Product]], we can also represent flux as:
$$
\Phi_{E}=\left| E \right| \cos\theta \left| A \right| 
$$
We only look at the portion of [[The Electric Field]] parallel to the area vector.

For curved surfaces, the area vector will be changing from place to place along the curved surface. So, we can use an integral to represent that variation:
$$
\Phi_{E}=\int\vec{E}\cdot d\vec{A}
$$
How do we determine $\vec{A}$? For closed surfaces, $\vec{A}$ is usually outwards. For open surfaces we can use the [[Right-hand Rule for Rotation]].

If we have a more complicated shape, like a cylinder, the total electric flux is the sum of the flux of each surface of the cylinder.

![[Pasted image 20250517215306.png]]


$$
\begin{align}
\oint \vec{E} \cdot  d\vec{A} & = \oint \vec{E}\cdot d\vec{A}_{1} +  \oint \vec{E}\cdot d\vec{A}_{2} +  \oint \vec{E}\cdot d\vec{A}_{3}
\end{align}
$$
