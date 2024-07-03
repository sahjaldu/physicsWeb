[[Coulomb's Law]] questions for AP Physics C; from College board.

## Finding the Location of a Third Charge.

>[!question]
>Suppose we have two point charges a distance of $4\mathrm{cm}$ apart, one with $5\mathrm{\mu C}$ on the left and another with $2\mathrm{\mu C}$. A third charge of $3\mathrm{\mu C}$ is placed along the same line in a location where it will not be moved. Where can the charge be placed?
>![[Pasted image 20240423094826.png]]

The charge will not move when all forces applied to it are net 0. In other words, all forces are equal.
$$
\begin{align}
\frac{kq_{1}q_{3}}{x^2}&=\frac{kq_{2}q_{3}}{(.04-x)^2} \\
\frac{\cancel{ k }q_{1}\cancel{ q_{3} }}{x^2}&=\frac{\cancel{ k }q_{2}\cancel{ q_{3} }}{(.04-x)^2} \\
(.04-x)^2&=\frac{q_{2}}{q_{1}}x^2 \\
(.04-x)^2&=\frac{2\times 10^{-6}}{5 \times 10^{-6}}x^2 \\ 
x^2-.08x+.0016&=.4x^2 \\
.6 x^2-.08x+.0016&=0 \\ \\
\text{Quadratic Formula:} \\
\frac{-.08\pm \sqrt{ (.08)^2-4(.6)(.0016) }}{2(.6)}&= \{.10,\ .025\} \\ \\
\boxed{ \text{2.5cm or 10cm} }
\end{align}
$$
Then we use [[Fundamental Law of Charges]] to determine which of the two is the best answer. Since opposite charges repel, it makes sense that the third charge would be away from the two charges, rather than in between. Therefore, we pick $\boxed{ \mathrm{10cm} }$.

