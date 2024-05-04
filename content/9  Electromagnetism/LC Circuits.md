An LC Circuit is a [[Circuits|Circuit]] with a [[Capacitors|Capacitor]] and a [[Inductors|Inductor]].

![[Pasted image 20240504012305.png]]

Here is what happens:
1. Initially, we have the left plate of the capacitor with a positive charge, and the right plate with a negative charge.
2. Charges move from the positive plate to the negative plate using the wire.
3. The Inductor resists the change in current from 0 but around the halfway point, when current should be slowing down to equilibrium, the Inductor resists the slowing down of current and positive charges instead continue to build up on the right plate.
4. Now the right plate has positive charge and the left plate has negative charge.
5. The process repeats in the other direction, and the charges continue to oscillate between both points.

Lets use [[Kirchhoff's Laws]] to create equations for the circuit:
$$
\begin{align}
V_{C} + V_{R} &= 0 \\
\frac{q}{C} + L \frac{ dI }{ dT } &= 0 \\
\frac{1}{LC}q +  \frac{ d^{2}q }{ dt^{2} }  &=0
\end{align}
$$
Note that the equation that we have now looks similar to that of a spring, or simple harmonic oscillator.
$$
\begin{align}
-kx&=ma \\
kx+m \frac{ d^{2}x }{ dt^{2} } &=0 \\
\frac{k}{m}x+ \frac{ d^{2}x }{ dt^{2} } &=0
\end{align}
$$
The sinusoidal equation for a simple harmonic oscillator looks like:
$$
x=x_{\mathrm{max}}\cos(\omega t+\phi)
$$
What we want is to make a sinusoidal equation for the charge oscillation in the circuit by replacing the variables from in the simple harmonic oscillator with the equation we derived from the circuit. We know that
$$
\begin{align}
\omega&=\frac{2\pi}{T} \\
T&=2\pi \sqrt{ \frac{m}{k} } \\
\omega&=\sqrt{ \frac{k}{m} }
\end{align}
$$
$k/m$ turns out to be the first part of the non-sinusoidal equation version of the simple harmonic oscillator. So, $x$ is replaced with $q$ and $k/m$ is replaced with $\frac{1}{LC}$.
$$
\begin{align}
\boxed{ q(t)=Q_{\mathrm{max}}\cos(\omega t+\phi) }\\
\text{where }\omega=\sqrt{ \frac{1}{LC} }
\end{align}
$$
We can differentiate this equation for the [[Current]]:
$$
\boxed{ I(t)= \frac{ dq }{ dt }  =-\omega Q_{\mathrm{max}}\sin(\omega t+\phi) }
$$
By adjusting the components of the circuit, we adjust $\omega$, thereby adjusting the oscillation frequency:
$$
f=\frac{1}{2\pi} \sqrt{ \frac{1}{LC} }
$$
This makes LC Circuits useful for devices to tune into specific frequency, like the radio.

Here are the graphs for charge and current:
![[Pasted image 20240504101329.png]]

And the graph for energy:
![[Pasted image 20240504101349.png]]
