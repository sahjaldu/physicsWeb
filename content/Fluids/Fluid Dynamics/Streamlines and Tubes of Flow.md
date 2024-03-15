## Streamlines
In [[General Concepts of Fluid Flow#^c750db|steady flow]], the velocity $\vec{v}$ of a given point is constant in time — meaning that $\vec{v}$ does not change. As a result, every [[Fluid Dynamics#^c18cf6|fluid particle]] arriving at $P$ will move with the same $\vec{v}$ to get to the next point, following a fixed path. This path is called a Streamline.

![[Pasted image 20240205153542.png|center]]

- The magnitude of the velocity vector $\vec{v}$ is always tangential to the streamline.
- No two streamlines can cross each other. Otherwise, fluid particles may have a choice on whether to go on one path or another path, meaning that it would not be fixed.
- In principle, we can draw a streamline through every point in the fluid.

## Tubes of Flow

By bundling streamlines together, we can create a region called a tube of flow.
- No fluid can cross the boundaries of a tube of flow.
- The fluid that enters at one end must leave the other.
- Typically when defining a tube of flow, we do it so that the tube is narrow enough so that the velocity is nearly constant over a cross-section.

![[Pasted image 20240205154528.png|center]]

In the image above:
- Fluid enters at $P$ with cross-sectional area $A_{1}$ and leaves at $Q$ with cross-sectional area $A_{2}$.
- Fluid particles at $P$ have velocity $v_{1}$ and fluid particles at $Q$ have velocity $v_{2}$.
- During an amount of time $\delta t$ a fluid element travels distance $v\,\delta t$.
- The fluid that crosses $A_{1}$ during $\delta t$ has volume $\delta V_{1}$.

If the density at $A_{1}$ is $\rho_{1}$, then the mass of fluid $\delta m_{1}$ is:
$$
\delta m_{1}=\rho_{1}\delta V_{1}=\rho_{1}A_{1}v_{1}\,\delta_{1}t
$$
We can use this to find *mass flux*, the mass of fluid passing through a cross section per unit time. At $P$ this is approximately: ^b84d6d
$$
\frac{\delta m_{1}}{\delta t}=\rho_{1}A_{1}v_{1}
$$
To get this value precisely, we must take the limit at $\delta t$ approaches $0$ so that the area $A$ does not change too much.

With the conditions that the flow is steady and there are no other sources or sinks, the fluid mass enters the tube at the same rate that is leaves it. As a result:
$$
\rho_{1}A_{1}v_{1}=\rho_{1}A_{2}v_{2}
$$
or:
$$
\Delta(\rho Av)=0
$$
This expresses the [[Law of Conservation of Mass]] in fluid dynamics.

If the fluid is incompressible, then the density remains the same:
$$
A_{1}v_{1}=A_{2}v_{2}
$$
or defining $R$ as the *volume flow rate*:
$$
\Delta R=\Delta (Av)=0
$$
$R$ has units $\mathrm{m^3/s}$.

Equations $\Delta (\rho Av) = 0$ and $\Delta R=\Delta (Av)=0$ are called the [[Equations of Continuity]] for one dimensional flow.