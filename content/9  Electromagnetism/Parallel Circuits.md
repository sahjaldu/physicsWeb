A parallel circuit is a type of [[Circuits|Circuit]] where there is more than one path for electrons to flow.

In other words:
>[!quote]
>"When a charge has the "choice" between two circuit elements and then the paths through those circuit elements reconverge without going through another circuit element, the two circuit elements are in *parallel*".

For example:

![[Pasted image 20240428154921.png]]

Because (positive) charges can either go through resistor 1 or resistor 2, the two resistors are in parallel.

Because there are multiple paths, the [[Current]] is divided.
$$
I_{T}=I_{1}+I_{2}
$$
The voltage at the positive terminal of the battery is $\epsilon$ and the voltage at the negative terminal of the battery is 0. Since there are no components between the negative terminal and the resistors, the voltage after the resistors must also be 0. We can reason:
$$
\epsilon=V_{1}=V_{2}
$$
We can use these two facts and [[Ohm's Law]] to get resistance:
$$
\begin{align}
I_{T}&=I_{1}+I_{2} \\
\frac{\epsilon}{R_{T}}&=\frac{V_{1}}{R_{1}}+\frac{V_{2}}{R_{2}} \\
\frac{\cancel{ \epsilon }}{R_{T}}&=\frac{\cancel{ V_{1} }}{R_{1}}+\frac{\cancel{ V_{2} }}{R_{2}} \\
\Aboxed{ R_{T}&=\frac{1}{\frac{1}{R_{1}}+\frac{1}{R_{2}}} }
\end{align}
$$
In general, for parallel components:
$$
\begin{align}
I_{T}&=I_{1}+I_{2}+\dots \\
V_{T}&=V_{1}=V_{2}=\dots \\
\frac{1}{R_{T}}&=\frac{1}{R_{1}}+\frac{1}{R_{2}}
\end{align}
$$
We can also calculate the total [[Capacitance]] in parallel circuits using $Q=CV$. Since:
$$
V_T = V_1 = V_2
$$

So the capacitors have the same charges on them, and we can calculate from there:
$$
\begin{align}
Q_T &= Q_1 + Q_2 \\
C_T V_T &= C_1 V_1 + C_2 V_2 \\
\Aboxed{C_T &= C_1 + C_2}
\end{align}
$$
In general for parallel circuits:
$$
C_T = C_1 + C_2 + \dots
$$