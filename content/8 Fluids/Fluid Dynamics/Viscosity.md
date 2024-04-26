Viscosity in fluid flow is similar to the concept of friction. If we want to keep a body at a constant velocity, we must have an external force to counteract the friction.

We can apply a similar logic to fluids by envisioning them as a series of plates.
![[Pasted image 20240308141022.png|100%]]

In the example, a force $\vec{F}$ is applied on the top plate so that it has constant velocity $\vec{v}$ compared to the bottom plate. $\vec{F}$ counteracts the viscous drag not only between the top plate and the fluid, but within the fluid itself. That is why we use the plates to specify that effect.

The speed of each layer differs by a $dv$, making this an example of laminar flow — one that uses [[Streamlines and Tubes of Flow]].

We know that the area of the top plate and each of the layers will have an effect on how much viscous drag there is, and thus the force $\vec{F}$ that we apply. We will thus say that force $F$ is proportional to the area $A$ times change in velocity that results from a change in the height of the layer. In mathematical terms, this is:
$$
F \propto A\frac{ dv }{ dy } 
$$
or, using $\eta$ as a constant of proportionality:
$$
F=\eta A\frac{ dv }{ dy }
$$
$\eta$ is the coefficient of velocity and it varies from fluid to fluid.

In the case for the rectangular layers above, the velocity gradient $dv / dy$ is constant, so we would instead write:
$$
F=\eta A \frac{v}{D}
$$
For a more practice example, we can look at viscosity in pipes.
![[Pasted image 20240314164513.png|100%]]

In this case, our layers are not rectangular but cylindrical with varying radii. Assuming that the layer next to the walls is at rest, the speed in a shell of radius $r$ is:
$$
v=\frac{\Delta p}{4\eta L}(R^2-r^2)
$$
Which depends on the pressure difference across the length of the pipe. The speed at the center of the pipe is:
$$
v_{0}=\frac{\Delta pR^2}{4\eta L}
$$
Using more derivation, we can show that the total [[Streamlines and Tubes of Flow#^b84d6d|mass flux]] is:
$$
\frac{ dm }{ dt } =\frac{\rho \pi R^4\Delta p}{8\eta L}
$$
This result is Poiseuille's Law.