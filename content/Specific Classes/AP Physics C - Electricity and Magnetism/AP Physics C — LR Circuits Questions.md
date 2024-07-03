![[Pasted image 20240504003003.png]]

>[!question]
>Determine the current through [[Resistance|Resistor]] 1 immediately after the switch closes.

The current through the [[Inductors|Inductor]] is zero because it resists change in current. So we use [[Ohm's Law]] for just the resistors:
$$
I=\frac{\epsilon}{R_{1}+R_{2}}
$$
>[!question]
>Determine the magnitude of the initial change in current in the inductor.

Since Resistor 2 and the Inductor are parallel, we can set their [[Electric Potential Difference|Voltage]] equal to each other.
$$
\begin{align}
V_{R_{2}}&=V_{I} \\
IR_{2}&=-L \frac{ dI }{ dt }  \\
\Aboxed{ \frac{ dI }{ dt }&=-\frac{R_{2}}{L}\left( \frac{\epsilon}{R_{1}+R_{2}} \right) }
\end{align}
$$
>[!question]
>Determine the voltage through the battery a long time after the switch is closed.

Current will flow through the Inductor rather than the resistor because the Inductor has much less resistance (a now negligible amount) than the resistor. So, we can just use Ohm's Law with R1.
$$
I=\frac{\epsilon}{R_{1}}
$$
>[!question]
>sketch a graph of the current as a function of time

![[Pasted image 20240504004803.png]]

>[!question]
>Some time after steady state, the switch is opened. Determine the voltage across resistor 2 just after the switch is opened.

We start by using the steady state current from the inductor.
$$
\begin{align}
I_{L}&=\frac{\epsilon}{R_{1}} =I_{R_{2}}=\frac{V_{R_{2}}}{R_{2}} \\
\frac{\epsilon}{R_{1}}&=\frac{V_{R_{2}}}{R_{2}} \\
\Aboxed{V_{R_{2}} &=\frac{\epsilon R_{2}}{R_{1}} }
\end{align}
$$
![[Pasted image 20240504005344.png]]
>[!question]
>Determine $I_{A}$, $I_{B}$, and $I_{C}$ immediately after the switch is closed.

Because the inductor resists change in current, $\boxed{ I_{C}=0 }$. So, we can use Ohm's Law for the rest:
$$
\boxed{ I_{A}=I_{B}=\frac{42}{22} =1.91\mathrm{A}}
$$
>[!question]
>Determine $I_{A}$, $I_{B}$, and $I_{C}$ a long time after the switch is closed.

After a long time, the voltage across the inductor is 0. For switch A:
$$
I_{A}=\frac{42}{10+\frac{1}{\frac{1}{12}+\frac{1}{6}}}=\frac{42}{14}=\boxed{ 3\mathrm{A} }
$$
$I_{A}=3 \mathrm{A}$ splits into $I_{B}$ and $I_{C}$. Since the resistance in $I_{B}$ is twice as much as the resistance in $I_{C}$, the current in $I_{B}$ is half as much as in $I_{C}$. So, $\boxed{ I_{B} = 1\mathrm{A} }$ and $\boxed{ I_{C} = 2\mathrm{A} }$.

>[!question]
>Sketch the magnitude of the potential difference across the inductor as a function of time, from immediately after the switch is closed to a long time after the switch is closed.

![[Pasted image 20240504010800.png]]

