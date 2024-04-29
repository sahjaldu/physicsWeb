Kirchhoff's Laws are two laws used to analyze complicated circuit.

>[!Definition] **Kirchhoff's Current Law**
>The current flowing into a node must equal the current flowing out of it.

For example:

![[Pasted image 20240429100210.png]]

$I_{1}$ is flowing into the node with $6\mathrm{A}$ and $I_{3}$ with $2\mathrm{A}$ and $I_{2}$ are flowing out of the node:
$$
\begin{align}
6\mathrm{A}&=I_{2}+2\mathrm{A} \\
\Aboxed{I_{2}&=4A}
\end{align}
$$

The other law is:
>[!Definition] **Kirchhoff's Voltage Law**
>The sum of all voltage differences around a closed loop is zero.

For example, with the circuit below:

![[Pasted image 20240429101546.png]]

We can find the missing resistance by using Kirchhoff's Voltage Law.

1. Pick an arbitrary point on the loop. Here, we will pick point $\mathrm{X}$.
2. Move along the loop, adding and subtracting voltages until we have completed the loop.
	1. Add the voltage of the battery, since voltage increases as we move from the negative to positive terminal.
	2. Use [[Ohm's Law]] to subtract the voltage drop at the resistor.
	3. Subtract the voltage of the second battery, since we are going from the positive to the negative terminal.
	4. Use Ohm's Law to subtract the voltage drop from the second resistor.
	5. Set equal to zero and solve.
$$
\begin{align}
10\mathrm{V}-(2\Omega \times 2\mathrm{A})-2\mathrm{V}-(R\times 2\mathrm{A})&=0 \\
6V&=R\times 2\mathrm{A} \\
\Aboxed{ 3\Omega&=R }
\end{align}
$$

[Some Practice](https://www.khanacademy.org/science/in-in-class-12th-physics-india/in-in-current-electricity/in-in-kirchhoffs-loop-rule/e/kirchhoff-s-loop-rule-numerical-exercises)
[Some more complicated examples](https://physics.info/kirchhoff/practice.shtml)
