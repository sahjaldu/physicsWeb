An LR Circuit is a [[Circuits|Circuit]] with an [[Inductors|Inductor]] and [[Resistance|Resistor]]. Here is an example of (a) a disconnected circuit, (b) the same circuit with $S_{1}$ closed, and (c) the same circuit with $S_{1}$ open and $S_{2}$ closed so that there is no battery powering the circuit
![[Pasted image 20240503203754.jpg]]

When the configuration changes from (a) to (b), the current increases from 0 to $\epsilon / R$ at a slower speed than if there were no inductor. When the configuration change from (b) to (c), The current should normally quickly drop back to 0. However, because the inductor resists changes in current, it takes time to do so, and there would still be current moving over the resistor during that time. In this way Inductors are similar to [[Capacitors]] and [[RC Circuits]].

Let's create a function for the change in current. We start off using [[Kirchhoff's Laws]] to analyze the circuit and moving from there. First, during charging in position (b):
$$
\begin{align}
0&=\epsilon - L \frac{ dI }{ dt } -IR \\
L \frac{ dI }{ dt }&=\epsilon -IR\\
\frac{dt}{L}&=\frac{dI}{\epsilon-IR} \\
\int_{0}^t \frac{dt}{L} &=\int_{0}^{I} \frac{dI}{\epsilon-IR} \\
\frac{t}{L}&=-\frac{1}{R}\ln(\epsilon-IR) + \frac{1}{R}\ln(\epsilon)\\
-\frac{Rt}{L}&=\ln\left( \frac{\epsilon-IR}{\epsilon} \right) \\
\epsilon e^{-Rt / L}&=\epsilon - IR \\
\frac{\epsilon}{R}-\frac{\epsilon e^{-Rt / L}}{R}&=I \\
\Aboxed{ I(t)&=\frac{\epsilon}{R}(1-\epsilon e^{-Rt / L}) }
\end{align}
$$
We can also define the final current $I_{f}=\epsilon / R$, and the time constant $\tau = L / R$:
$$
I(t) = I_{f}(1 - \epsilon e^{-t/\tau})
$$
Using the equation from before, we can also calculate the potential difference across the resistor.
$$
\begin{align}
V=IR=\epsilon(1-\epsilon e^{-Rt / L})
\end{align}
$$
And potential difference across the inductor:
$$
V=-L \frac{ dI }{ dt } =\epsilon e^{-Rt / L}
$$
Now lets find the equation for discharging:
$$
\begin{align}
0&=-L \frac{ dI }{ dt } -IR \\
-\frac{L}{R} \frac{ dI }{ dt }  &= I \\
-\frac{R\,dt}{L}&=\frac{dI}{I} \\
\int_{0}^t -\frac{R\,dt}{L} &= \int_{0}^I \frac{dI}{I} \\
-\frac{R}{L} t +K'&=\ln(I) \\
K&=e^{K'} \\
Ke^{-Rt/L}&=I \\
K&=\frac{\epsilon}{R} \\
\Aboxed{ I(t)&=\frac{\epsilon}{R}e^{-Rt / L} }
\end{align}
$$
The potential difference across the resistor:
$$
V=IR=\epsilon e^{-Rt / L}
$$
and across the Inductor:
$$
V=-L \frac{ dI }{ dt } = -\epsilon e^{-Rt / L}
$$
For AP Physics C students, make sure you know how to graph each of these equations.