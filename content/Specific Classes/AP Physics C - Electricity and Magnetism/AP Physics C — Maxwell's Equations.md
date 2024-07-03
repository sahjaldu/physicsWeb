Maxwell's Equations bring the various equations for electromagnetism together in a simple and elegant way. So far we have two equations from [[Gauss's Law|Gauss]]:
$$
\begin{align}
\oint \vec{E} \cdot d \vec{A} &= \frac{Q_{\mathrm{enc}}}{\epsilon_{0}} \\
\oint \vec{B} \cdot d \vec{A} &= 0
\end{align}
$$
An equation from [[Faraday's Law|Faraday]]:
$$
\epsilon=\oint \vec{E} \cdot d \vec{l} = - \frac{ d \Phi_{B} }{ dt } 
$$
And an equation from [[Ampere’s Law|Ampere]] with [[Displacement Current]]:
$$
\oint \vec{B} \cdot d \vec{l} = \mu_{0}I + \mu_{0} \epsilon_{0} \frac{ d \phi_{E} }{ dt } 
$$
Maxwell's Equations use [[Curl]] and [[Divergence]] in [[Vector Field|Vector Fields]]. Essentially:
- Curl describes how vectors bend/circle. It is represented as $\nabla \cdot \vec{V}$.
- Divergence describes how the vectors spread out. We can use it as a [[Electric Flux|Flux]] quantity; for example, how much electric flux flows out of an area. It is represented as $\nabla \times \vec{V}$.

Gauss's Law says that the electric field times an area is proportional to the charge enclosed by that area. It describes how the electric field diverges or converges from electric charges. We can write it as:
$$
\nabla \cdot \vec{E} = \frac{\rho}{\epsilon_{0}}
$$
Gauss's Law for magnetic just says that magnetic field lines are always closed loops from north to south. As a result, there is no net divergence or convergence of magnetic field — it just loops around.
$$
\nabla \cdot \vec{B} = 0
$$
Faraday's Law says that an electric field within a loop induces a magnetic field. More specifically, electric field lines curl around changing magnetic fields.
$$
\nabla \times \vec{E} = -\frac{ d\vec{B} }{ dt } 
$$
Ampere's law says that magnetic field will curl around currents. We then add displacement current to the end.
$$
\vec{\nabla} \times \vec{B} = \mu_{0} J + \mu_{0} \epsilon_{0} \frac{ d \phi_{E} }{ dt } 
$$
When we put these equations together we find that {Blanks}. Lets look at these laws for empty space with no extra fields.
$$
\begin{align}
\oint \vec{E} \cdot d\vec{A} &= \cancel{ \frac{Q_{\mathrm{enc}}}{\epsilon_{0}} } \\
\oint \vec{B} \cdot d \vec{A} &= 0 \\
\oint \vec{E} \cdot d\vec{l} &= -\frac{d}{dt} \left( \int \vec{B} \cdot \, d\vec{A}  \right) \\
\oint \vec{B} \cdot d\vec{l} &= \cancel{ \mu_{0}I_{\mathrm{enc}} } + \mu_{0}\epsilon_{0} \frac{ d \phi_{E} }{ dt }  \\
\end{align}
$$
Here are all the terms that don't go to zero:
$$
\begin{align}
\oint \vec{E} \cdot d\vec{l} &= \frac{ d\Phi_{B} }{ dt } \\
\oint \vec{B} \cdot d\vec{l} &= \mu_{0}\epsilon_{0} \frac{ d\phi_{E} }{ dt } 
\end{align}
$$
An electric field is created from a magnetic flux change and a magnetic field is created from an electric flux change. Therefore, if in empty space an electric flux is made to change over time, then a magnetic flux is created. If that magnetic flux changes with time, that creates an electric flux. This process repeats over and over again with magnetic/electric fields propagating outwards through space.
![[propagation-of-electromagnetic-waves-ec98e4d0.webp]]
This is what light is. Light is an electromagnetic wave that propagates through space as electric fields and magnetic field create one another.