![[Pasted image 20240503134040.png]]

>[!question]
>a) What is the direction of the [[Current]] in the [[Resistance|Resistor]].

Since the area of the loop increases as the bar moves, the [[Magnetic Flux]] increases. Per [[Lenz's Law]], a magnetic field opposite to that of the current [[The Magnetic Field|Magnetic Field]] is induced. In other words, the magnetic field into the page decreases. Using the [[Right-hand Rule for Rotation]], we can find that there is a counter-clockwise current, and that the direction of the current in the resistor is left.

>[!question]
>bi) Is the magnitude of the net magnetic field above the bar at point $C$ greater than, less than, or equal to the magnitude of the net magnetic field before the bar is released?

It is less than. the magnetic field into the page decreases as an induced magnetic field opposing the current magnetic field is created by the increasing magnetic flux.

>[!question]
>bii) While the bar is above point $D$, is the magnitude of the net magnetic field at point $D$ greater than, less than, or equal to the magnitude of the net magnetic field before the bar is released?

Greater than. Recall that the magnetic field loops around a current carrying wire. As a result of this fact, the magnetic field induced outside the loop will be pointing downwards, increasing the net magnetic field into the page.

- - -
Express answers to part (c) and (d) in terms of $M$, $L$, $R$, $B$, and physical constant as appropriate.
- - -

>[!question]
>c) Write but do not solve a differential equation that could be used to determine the velocity of the falling bar as a function of time.

$$
\begin{align}
\sum F &= F_{g} - F_{B} \\
&=Mg - BIL \\
I &= \frac{\epsilon}{R} \\
\epsilon &= BL \frac{dx}{dt} \\
&=BLv \\
I&=\frac{BLv}{R} \\
Ma &= Mg - \frac{B^2L^2v}{R} \\
a&=g-\frac{B^2L^2v}{MR} \\
\frac{ dv }{ dt } &=g - \frac{B^2L^2v}{MR}
\end{align}
$$
>[!question]
>d) Determine an expression for the terminal velocity $v_{T}$ of the bar.

Terminal velocity occurs when the acceleration is zero.
$$
\begin{align}
0 &= g - \frac{B^2L^2v_{T}}{MR} \\
\frac{B^2L^2v_{T}}{MR} &=g \\
\Aboxed{ v_{T} &= \frac{gMR}{B^2L^2} }
\end{align}
$$
- - -
Express your answers to part (e) and (f) in terms of $v_{T}$, $M$, $L$, $R$, $B$, and other physical constants as appropriate.
- - -
>[!question]
>e) Derive an expression for the power dissipated in the resistor when the bar is falling at terminal velocity

$$
\begin{align}
P &= I^2 R \\
&=\left( \frac{BLv_{T}}{R} \right)R \\
&=\frac{B^2L^2v_{T}^2}{R^2} R \\
P&=\frac{B^2L^2v_{T}^2}{R}
\end{align}
$$
>[!question]
>f) Using your differential equation from part (c), derive an expression for the speed of the falling bar $v(t)$ as a function of time.

$$
\begin{align}
\frac{ dv }{ dt } &=g - \frac{B^2L^2v}{MR} \\
&=-\frac{B^2L^2}{MR}v- \frac{gMR}{B^2L^2} \\
\frac{dv}{v-\frac{gMR}{B^2L^2}}&=-\frac{B^2L^2}{MR}dt \\
\int_{0}^{v_{T}} \frac{dv}{v-\frac{gMR}{B^2L^2}} &=-\frac{B^2L^2}{MR} \int_{0}^t \, dt \\
u &= \frac{gMR}{B^2L^2} \\
\ln[v-u]_{0}^{v_{T}}&=-\frac{B^2L^2}{MR}t  \\
\ln[v_{T}-u] - \ln[-u]&=-\frac{B^2L^2}{MR}t \\
\ln\left[ -\frac{v_{T} - u}{u} \right] &=-\frac{B^2L^2}{MR}t \\
-\frac{v_{T}}{u} +1 &= e^{\Large -\frac{B^2L^2}{MR}t} \\
v_{T}&=-u\left( -1+e^{\Large -\frac{B^2L^2}{MR}t} \right) \\
\Aboxed{ v(t)&=\frac{gMR}{B^2L^2}\left(1-e^{\Large -\frac{B^2L^2}{MR}t} \right) }
\end{align}
$$
