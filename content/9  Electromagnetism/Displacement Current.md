Displacement Current is [[AP Physics C — Maxwell's Equations|Maxwell's]] addition to [[Ampere’s Law]].

For the capacitor below:

![[Pasted image 20240504111236.png]]

We can find [[The Magnetic Field]] at point $P$ using [[Ampere’s Law]]. We form an Amperian Loop around point $P$ and see that the [[Current]] enclosed is $I$, and that therefore there is a Magnetic Field at $P$.

Between the two plates there is no current, so when we form our Amperian loop, there should also be no Magnetic Field at point $Q$. However, observational evidence says otherwise. A Magnetic Field does form between the currents. In fact, the magnetic field at $P$ equals the magnetic field at point $Q$.

This means that Ampere's Law is missing some component, and Maxwell was able to find that component. He reasoned that if a change in [[Magnetic Flux]] created an [[The Electric Field|Electric Field]], then a change in [[Electric Flux]] created a magnetic field. The complete equation would be:
$$
\oint \vec{B} \cdot d\vec{l} = \mu_{0} \left( I_{\mathrm{enc}}+\epsilon_{0} \frac{ d\phi_{E} }{ dt }  \right)
$$
The $I_{\mathrm{enc}}$ is the conduction current and $\epsilon_{0}\ d\phi_{E} / dt$ is the displacement current.

The derivation for this is as follows. We start by using [[Gauss's Law]] over the positive plate of the capacitor:
$$
\begin{align}
\oint \vec{E} \cdot d\vec{A} &= \frac{Q_{\mathrm{enc}}}{\epsilon_{0}} \\
E(A)&=\frac{Q}{\epsilon_{0}} \\
E&=\frac{\sigma}{\epsilon_{0}}
\end{align}
$$
Then we look at the charge of the capacitor:
$$
\begin{align}
C&=\frac{Q}{V}= \frac{ dq }{ dv_{c} }  \\
dq &= C \,dv_{c} \\
\frac{ dq }{ dt } &= C \frac{ dv_{c} }{ dt } \\
I_{0}&=\frac{C\,d(Ed)}{dt}
\end{align}
$$
Then we look at the capacitance:
$$
\begin{align}
C&=\frac{Q}{V} \\
&=\frac{E\epsilon_{0}A}{Ed} \\
&=\frac{A\epsilon_{0}}{d}
\end{align}
$$
And plug it in:
$$
\begin{align}
I_{0}&=\frac{A\epsilon_{0}}{d} \frac{d(Ed)}{dt} \\
&=\epsilon_{0} \frac{d(EA)}{dt} \\
&=\boxed{ \epsilon_{0} \frac{d \phi_{E}}{dt} }
\end{align}
$$
