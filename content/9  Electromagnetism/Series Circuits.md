A Series Circuit is a type of [[Circuits|Circuit]] where there is only one path for electrons to flow.

In other words:
>[!quote]
>"Two circuit elements are in *series* when every charge must go through both circuit elements. (There are no other paths for the charges to "choose" to go through.)"

For example:

![[Pasted image 20240427192251.png]]

Every charge must go through Resistor 1, Resistor 2, and Resistor 3. The three resistors are in series.

Each resistor also causes a drop in voltage. Because the voltage at the positive terminal is $\epsilon$ and at the negative terminal it is $0$ we can say:
$$
\epsilon=V_{1}+V_{2}+V_{3}
$$
Additionally, the current is constant because [[Kirchhoff's Laws|there is only one path for the current to flow]]. So:
$$
I_{T}=I_{1}+I_{2}+I_{3}
$$
Using these two facts and [[Ohm's Law]], we can find the resistance:
$$
\begin{align}
\epsilon&=V_{1}+V_{2}+V_{3} \\
I_{T}R_{T}&=I_{1}R_{1}+I_{2}R_{2}+I_{3}R_{3} \\
\cancel{ I_{T} }R_{T}&=\cancel{ I_{1} }R_{1}+\cancel{ I_{2} }R_{2}+\cancel{ I_{3} }R_{3} \\
\Aboxed{ R_{T}&=R_{1}+R_{2}+R_{3} }
\end{align}
$$
In general for series components:
$$
\begin{align}
I_{T}&=I_{1}=I_{2}=\dots \\
V_{T}&=V_{1}+V_{2}+\dots \\
R_{T}&=R_{1}+R_{2}+\dots
\end{align}
$$
We can also calculate the total [[Capacitance]] in series circuits as:
$$
\begin{align}
V_T &= V_1 + V_2 + V_3 \\
\frac{Q}{C_T} &= \frac{Q}{C_1} + \frac{Q}{C_2} + \frac{Q}{C_3} \\
\Aboxed{\frac{1}{C_T} &= \frac{1}{C_1} + \frac{1}{C_2} + \frac{1}{C_3}} \\
\end{align}
$$

In general for series circuits:
$$
\frac{1}{C_T} = \frac{1}{C_1} + \frac{1}{C_2} + \dots
$$
