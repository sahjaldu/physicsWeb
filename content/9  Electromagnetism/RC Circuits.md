[source](https://phys.libretexts.org/Bookshelves/University_Physics/University_Physics_(OpenStax)/Book%3A_University_Physics_II_-_Thermodynamics_Electricity_and_Magnetism_(OpenStax)/10%3A_Direct-Current_Circuits/10.06%3A_RC_Circuits)
An RC Circuit is a circuit with a [[Capacitors|Capacitor]] and a [[Resistance|Resistor]].

For example:
![[Pasted image 20240429121649.jpg]]

(a) is the original state with an uncharged capacitor, (b) is the state where the capacitor is charging, and (c) is the state where the capacitor is being discharged.

We can find equations for charge and current at the capacitor during charging and discharging:

## Charging:

Steps:
1. Use [[Kirchhoff's Laws]] to get an equation for the circuit
2. Replace current and charge at resistor with values that can be used to take a derivative.
3. Rearrange and integrate
4. Simplify using $e^t$ form
$$
\begin{align}
\epsilon-V_{R}-V_{C}&=0 \\
\epsilon-IR-\frac{Q}{C}&=0 \\
\epsilon-R \frac{ dq }{ dt } -\frac{q}{C}&=0  \\
\frac{ dq }{ dt } &=\frac{\epsilon-\frac{q}{C}}{-R} \\
\frac{ dq }{ dt } &=\frac{C\epsilon-q}{RC} \\
\int_{0}^q \frac{1}{C\epsilon-q} \, dq &= \frac{1}{RC} \int_{0}^t \, dt  \\
-\int_{0}^q \frac{du}{u} \, &= \frac{1}{RC} \int_{0}^t \, dt  \\
\ln\left( \frac{\epsilon C-q}{\epsilon C} \right) &= -\frac{1}{RC}t \\
\frac{\epsilon C-q}{\epsilon C}&=e^{-t / RC} \\
1 - \frac{q}{\epsilon C}&=e^{-t / RC} \\
-\frac{q}{\epsilon C} &= 1 + e^{-t / RC}\\
\Aboxed{q(t)=\epsilon C(1-e^{-t / RC})&=Q(1-e^{-t / \tau})}
\end{align}
$$
At the end, we simplified $RC=\tau$ as the time constant.

We can use this new equation for charge to find [[Current]] as the capacitor charges:
$$
\begin{align}
I &= \frac{ dq }{ dt }  \\
&=\frac{d}{dt}[ \epsilon C(1-e^{-t / RC})] \\
&= \frac{ dq }{ dt }  [\epsilon C - \epsilon Ce^{-t / RC}] \\
&= -\epsilon C \frac{-1}{RC} e^{-t / RC} \\
&= \frac{\epsilon}{C} e^{-t / RC} \\
\Aboxed{I(t)&=I_{0}e^{-t / RC}}
\end{align}
$$

We can model these two equations on a graph. $Q(t)$ has the shape of an $1-e^{-x}$ graph and $I(t)$ has the shape of an $e^{-x}$:

![[Pasted image 20240429140712.jpg]]

We get the bottom two equations by putting the equation in terms of $\epsilon$. 

## Discharging

We use a similar method for discharging
$$
\begin{align}
-V_{R}-V_{C}&=0 \\
-R \frac{ dq }{ dt } -\frac{q}{C}&=0 \\
\frac{ dq }{ dt } &=-\frac{q}{RC} \\
-\int_{0}^q \frac{1}{q} \, dq &= \frac{1}{RC} \int_{0}^t \, dt \\
\ln \left( \frac{q}{Q} \right) &= -\frac{1}{RC}t \\
\Aboxed{ q(t)&=Qe^{-t / RC}  }
\end{align}
$$
And then we turn that equation into the one for current:
$$
\begin{align}
I&=\frac{ dq }{ dt }  \\
&=\frac{d}{dt} Qe^{-t / RC} \\
&=-\frac{Q}{RC}e^{-t/RC}
\end{align}
$$

![[Pasted image 20240429143654.jpg]]