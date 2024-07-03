A Solenoid is a tightly compacted coil of wire, much like a slinky.
![[Pasted image 20240502194431.png|500]]
It has a number of turns $N$, a length $l$, and a radius $r$.

When it carries a [[Current]] $I$, a [[The Magnetic Field|Magnetic Field]] $B$ is created inside the solenoid. The outside magnetic field is negligible.

As you get closer to the ends of a solenoid, the magnetic field breaks down. We typically only look at the magnetic field in the center of the solenoid. An "ideal" solenoid is infinitely long.

We can use [[Ampere’s Law]] to find the magnetic field $\vec{B}$ inside the solenoid. Our Amperian Loop will be rectangular as seen below:

![[Pasted image 20240502193339.png]]

Then we do the math:
$$
\begin{align}
\oint \vec{B} \cdot d\vec{l}&=\mu_{0}I_{\mathrm{enc}} \\
\sum B \cdot d\vec{l} &= B_{\mathrm{AB}}\,l+ B_{\mathrm{BC}}\,l + B_{\mathrm{CD}}\,l+B_{\mathrm{DA}}\,l \\
&=B_{\mathrm{AB}}\,l \\
B_{\mathrm{AB}}l&=\mu_{0}I_{\mathrm{enc}} \\ \\
 I_{\mathrm{enc}}&=IN \\
\frac{N}{l}&=n \\
I_{\mathrm{enc}}&=Inl \\ \\
B_{\mathrm{AB}}l&=\mu_{0}Inl \\
\Aboxed{B&=\mu_{0}nI}
\end{align}
$$