A vector is a point with a direction. Oftentimes, they are represented by an arrow. They are also represented as a list of numbers (or other stuff, like functions).

When it is a list of numbers, we can think of it as an arrow in space.
For example, we visualize the vector $(4,2)$ as an arrow whose tail is at the origin and whose tip is at the point $(4, 2)$.

Sometimes we draw the vector with the tail not on the origin. The $(4, 2)$ vector shifted up so that it starts at $(0, 2)$ is still called the $(4, 2)$ vector.

This is why it can sometimes be confusing to have vectors act like points in space.

## Notation

Three ways to write vectors:
$$
\vec{v}=(1, 2, 3)=
\begin{bmatrix}
1 \\
2 \\
3
\end{bmatrix}
=1\hat{i} + 2\hat{j} + 3\hat{k}
$$
For $\vec{v}$, the arrow is a convention that shows that it is a vector.
- The first notation is the **point notation**, which can extend to any number of dimensions
- The second notation is Matrix notation, which can also be extended to any amount of dimensions. This notation is useful when vectors interact with matrices.
- The third notation only works in 2D and 3D. It uses Unit Vectors $\hat{i}$ ("I-hat"), $\hat{j}$, and $\hat{k}$
	- $\hat{i}=(1, 0, 0)$ and is the unit $x$ vector.
	- $\hat{j}=(0, 1, 0)$ and is the unit $y$ vector.
	- $\hat{k}=(0, 0, 1)$ and is the unit $z$ vector.

We usually use the first notation in exercises

## Vector Addition

In general, whenever we add two vectors, we add their corresponding components.
$$
(a, b, c) + (A, B, C)= (a+A, \ b+B, \ c+C)
$$
We can visualize this as:

![[Drawing 2023-11-12 17.59.19.excalidraw|700]]



## Scalar Multiplication

This is when we stretch or shrink a vector by a Scalar, which is just a regular number.

$$\vec{b}=(1, 2, 3)$$
$$
2\vec{b}=(2, 4, 6)
$$

In general, this just means we multiply each component by the scalar.

$$
x \vec{a} = x(a, b, c)= (xa, xb, xc)
$$

When we multiply a vector by -1, we flip the vector.

## Magnitude

We write the magnitude, or length, of the vector $\vec{a}$ like $\lvert \lvert \vec{a} \rvert \rvert$ or $\lvert \vec{a} \rvert$.

We can calculate the magnitude with the Pythagorean theorem.

## [[Dot Product]]

The dot product of two vectors is a number that tells us how much two vectors point in the same direction.

$$
\vec{a} \cdot \vec{b} = \lvert \lvert \vec{a} \rvert  \rvert \ \lvert \lvert \vec{b} \rvert  \rvert \cos (\theta)
$$

In simple terms, it is the magnitude of both vectors times the cosine of the angle between the two vectors.

When $\theta = 0$, the vectors point in the same direction. This is when the dot product is at its largest, because $\cos(0) = 1$.

When $\theta = \frac{\pi}{2}$, the vectors are perpendicular to each other.

When $\theta = 1$, the vectors are opposite each other. 

We usually have to compute the dot product a lot. Therefore, a shortcut is to multiply corresponding components and then add.

$$
\vec{a} = (a_{1}, a_{2}, a_{3})
$$
$$
\vec{b}=(b_{1}, b_{2}, b_{3})
$$
$$
\vec{a} \cdot  \vec{b} = a_{1}b_{1} + a_{2} + b_{2} + a_{3}b_{3}
$$

This formula extends to vectors of any length.

## [[Cross Product]]

The cross product between two vectors returns another vector. A vector $\vec{c}$ where $\vec{a} \times  \vec{b} = \vec{c}$ has two properties.
1. $\vec{c}$ is perpendicular to both $\vec{a}$ and $\vec{b}$. In terms of the dot product, we can say that
$$
\vec{c} \cdot  \vec{a} = \vec{c}  \cdot  \vec{a} = 0
$$
This also means that the cross product only works in three dimensions. In four dimensions, there are infinitely many vectors perpendicular to two vectors (Think of it as a line of perpendiculars).
2. The length of $\vec{c}$ is a measure of how far apart $\vec{a}$ and $\vec{b}$ are pointing, augmented by their magnitudes.
$$
\lvert \lvert \vec{c} \rvert  \rvert = \lvert \lvert \vec{a} \rvert  \rvert  \ \lvert \lvert \vec{b} \rvert  \rvert \sin(\theta)
$$
It looks like the dot product with a sine instead of a cosine. Because of this, when the angle is 90 degrees, the cross product is largest. This makes the dot product and cross product complement each other.

One interpretation of the length of $\vec{c}$ is very useful.

![[Pasted image 20231112220351.png]]

The base of the parallelogram has length $\lvert \lvert \vec{a} \rvert \rvert$ and the height has length $\lvert \lvert  \vec{b} \rvert \rvert$. The area of the parallelogram is the magnitude of the cross product (base times height).

### The Right-hand Rule

You might have noticed that in a three-dimensional plane, there are actually two ways a third vector can be perpendicular to two other vectors. In order to decide which one, we use the [[Right-hand Rule]]. 

![[e0259a0176f59362b439094f6fa12e469468c97d.svg]]

### Cross Product Formula

For:
$$
\vec{a} = (a_{1}, a_{2}, a_{3})
$$
$$
\vec{b}=(b_{1}, b_{2}, b_{3})
$$
$$
\Large
\vec{a} \times \vec{b} = 
\begin{bmatrix}
a_{2}b_{3} - a_{3}b_{2} \\
a_{3}b_{1} - a_{1}b_{3} \\
a_{1}b_{2} - a_{2}b_{1}
\end{bmatrix}
$$
The cross product here is a 3D Determinant.