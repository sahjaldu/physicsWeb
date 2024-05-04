Inductors are coils of wire that can self-induce an emf and therefore a [[Current]]. The coil has an Inductance $L$ where:
$$
L=N \frac{\Phi_{B}}{I}
$$
Where:
- $N$ is the number of coils
- $\Phi_{B}$ is the [[Magnetic Flux]]

Inductance is measured in Henrys ($\mathrm{H}$)
![[Pasted image 20240503183210.jpg]]

Inductors in [[Circuits]] oppose change in the current of the circuit. Therefore, they are used in surge protectors, slowing down any rapid change in the current from a power surge.

The basic relationship between [[Electric Potential Difference|Voltage]], current, and inductance is:
$$
\epsilon=V=-L \frac{dI}{dt}
$$
Where the voltage equals the inductance of the inductor times the change in voltage over time. In general, a larger inductance means that it can slow a change in current more.

An inductor has a magnetic field shaped like this:

![[Pasted image 20240503201751.png]]
When there is an increase in current, that means that there is an increase in magnetic field, meaning an increase in magnetic flux. By [[Lenz's Law]], because the magnetic flux increases, we induce a magnetic field opposing the current magnetic field. As a result, the magnetic field decreases, inducing an opposing current, which resists the initial increase in current. Vice Versa for an initial decrease in current.

From this process, we say an Inductor is "Self-Inductive".

We can analyze the behavior of inductors using [[Faraday's Law]] for inductors:
$$
\oint \vec{E} \cdot d\vec{l} = - \frac{ d\Phi_{B} }{ dt }
$$
The left half of the equation is a line integral coming from the fact that $V = -\int \vec{E} \, dr$.

The Energy stored in a conductor (As Magnetic Energy):
$$
\frac{1}{2}LI^2
$$
A good metaphor for inductance is mass. A larger mass resists changes in velocity. 
## Inductance of a Solenoid

First, we get the magnetic flux. We do this by using the [[AP Physics C — Magnetic Field inside and outside a solenoid|Magnetic Field of a Solenoid]]. Then we plug this into the equation for inductance.
$$
\begin{align}
\Phi_{B} &= \vec{B} \cdot \vec{A} = BA \\
B &= \frac{\mu_{0}NI}{l} \\
L&=\frac{N}{I} \frac{\mu_{0}NI}{l}  A \\
&=\boxed{ \frac{\mu_{0}N^2A}{l}}
\end{align}
$$
