We will use [[Newton's Second Law]], [[Faraday's Law]], and [[Lenz's Law]] to analyze a conductive Bar's Motion on rails.

The loop of wire below has width $w$, height $h$, and contains a switch and a battery. It is connected to a spring of force constant $k$. The loop carries a [[Current]] $I$ moving clockwise and the loop's bottom has a uniform magnetic field $\vec{B}$ pointing into the page.
![[Pasted image 20240503125428.png]]

>[!question]
>a) Indicate the direction of the magnetic forces that act on each side of the loop.

![[Pasted image 20240503125935.png]]

>[!question]
>b) The switch is opened and the loop eventually comes to rest at a new equilibrium position that is a distance $x$ from its former position. Derive an expression for the magnitude $B_{0}$ of the uniform magnetic field in terms of the given quantities and fundamental constants.

Since the loop has come to rest, the net force must be zero. So, the spring force and magnetic force must be equal (we say gravitational is negligible)
$$
\begin{align}
F_{B}&=F_{S} \\
IwB_{0}&=-k x \\
B_{0}&=-\frac{kx}{Iw}
\end{align}
$$
- - -
The spring and loop are replaced with a loop of the same dimensions and [[Resistance]] $R$ but without the battery and switch. The new loop is pulled upward, out of the magnetic field at a constant speed $v_{0}$. Express algebraic answers to the following questions in terms of $B_{0}$, $v_{0}$, $R$, and the dimensions of the loop
![[Pasted image 20240503131414.png]]

>[!question]
>c) Indicate the direction of the induced current in the loop as the loop moves upward.

If we are pulling the loop up, then the area $A$ overlapping with $B_{0}$ is decreasing, so flux $\Phi_{B}$ is decreasing. Therefore, a new magnetic field is created in the same direction as the current magnetic field, and $B_{0}$ into the page increases. Using the [[Right-hand Rule for Rotation]] we can find that the direction of induced current is clockwise.

>[!question]
>Derive an expression for the magnitude of this current.

We can use Faraday's Law:
$$
\begin{align}
\epsilon &= \frac{ d\Phi_{B} }{ dt } \\
I&=\frac{\epsilon}{R} \\
&=\frac{d\Phi_{B}}{R\,dt} \\
&=\frac{wB_{0}}{R} \frac{dh}{dt} \\
\Aboxed{ I&=\frac{B_{0}w\,v_{0}}{R} }
\end{align}
$$
>[!question]
>d) Derive an expression for the power dissipated in the loop as the loop is pulled at constant speed out of the field.

[[Power]] is $P = -\frac{ dE }{ dt }$. In this case we use [[Electric Power]] $P = I\Delta V$.
$$
\begin{align}
P&=IV \\
&=I^2R \\
&=\frac{B_{0}^2 w^2 v_{0}^2}{R^2}R \\
&=\frac{B_{0}^2 w^2 v_{0}^2}{R} \\
\end{align}
$$
>[!question]
>Suppose the magnitude of the magnetic field in increased. Does the external force required to pull the loop at speed $v_{0}$ increase, decrease, or remain the same?

$F_{B}=IwB_{0}$. If $B_{0}$ increases, then $F_{B}$ increases. Therefore, to keep the loop moving at $v_{0}$, a larger force applied must be used.