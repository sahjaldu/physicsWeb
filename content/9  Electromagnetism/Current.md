Current is the rate at which charge flows through a [[Circuits|Circuit]]:
$$
\boxed{ I=\frac{dQ}{dt} }
$$
Current is measured in $A$ (Amps), $Q$ is the total charge moving though a given point, and $t$ is the time it take to pass through that point.

On a smaller level, we can get more specific:
$$
\begin{align}
Q&=neAd, \hspace{ 0.5in } t=\frac{d}{v_{d}} \\
I&=\frac{Q}{t} =\frac{neAd}{\frac{d}{v_{d}}} =\boxed{ neAv_{d} }
\end{align}
$$
Where: 
- $n$ is the number of charges per volume
- $e$ is the charge for each charge
- $A$ is the cross-sectional area of the wire
- $d$ is a small distance on the wire

And:
- $t$ is the time needed for the charge to move over $d$
- $v_{d}$ is the drift velocity, the average velocity of the charge carriers (since they don't move in straight lines; they also bump around, speed up/slow down, etc.)

We can also define current as Current Density $J$, current per cross sectional area: ^8f066f
$$
\begin{align}
i = \int_{S} \vec{j}  \cdot  d\vec{S}
\end{align}
$$
Where $\rho$ is the [[Resistivity]] of the wire.

Note that in a [[Circuits|Circuit]] conventional current, the one typically used, flows from positive to negative, even though electrons are the charges moving. This is because this was worked out before it was reasoned that electrons were moving from the negative to the positive side, but the overall effect is the same. The current that used the electron flow direction is called the electron current.

Charges are conserved throughout a wire — currents can't appear/disappear out of nothing, they are moving charges towards or away from somewhere. So for some arbitrary region enclosed by some surface,
$$
\oint_{S} \vec{j} \cdot d\vec{S} = i_{\mathrm{out}} = \frac{dq_{\mathrm{in}}}{dt}
$$
If we have steady-state currents (currents are constant):
$$
\frac{dq_{\mathrm{in}}}{dt} = 0,\hspace{ 0.4in } \oint_{S} \vec{j} \cdot d\vec{S} = 0
$$
Since charges in a region of space are not changing, the electric field from some region of space will not change – constant in time. The electric fields are still conservative, so potential functions are still valid.

