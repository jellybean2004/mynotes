- revisiting [[PX157 - C2 - force of current loops#force on a moveable bar|force on a moveable bar]], but now, there is no power source

![[Pasted image 20240226181151.png]]
- the crossbar is forced externally to move at velocity, $\vec v = v\,\hat x$
- in the time-interval, $\Delta t$, the crossbar will have moved by a distance, $\Delta x = v\,\Delta t$
- area enclosed by the crossbar increases: $$\Delta A = \Delta x\,L= v\,\Delta t\,L$$
- the magnetic flux increases: $$\Delta\phi_{B}= B\,\Delta A = BvL\,\Delta t$$
- the rate of change in magnetic flux: $$\frac{\Delta\phi_{B}}{\Delta t} = BvL$$
- from [[PX157 - D1a - faraday's law|faraday's law]], and using the right-hand rule (emf points counter-clockwise): $$\epsilon = -BvL$$
- emf drives a current in the counter-clockwise direction: $$I = \frac{|\epsilon|}{R} = \frac{BvL}{R}$$
- force on a section $d\vec l$ of the crossbar due to the induced current: $$\begin{align*}
	d\vec F &= I\, d\vec l \times \vec B \\
	&= I\,dl\, B \,\hat y\times (-\hat z) \\
	&= - I\,dl\,B\,\hat x
\end{align*}$$
- total force on the crossbar: $$\vec F = - IB\int dl\,\hat x  = -IBL\,\hat x$$
- if there is no external forcing: $$\begin{align*}
	m\, \frac{dv}{dt} &= - IBL \\
	&= - \frac{B^{2}L^{2}}{R}v \\
	\implies \frac{dv}{dt} &= - \frac{v}{\tau}
\end{align*}$$
		where, $\tau = \left(\frac{B^{2}L^{2}}{Rm}\right)^{-1}$
- the solution for the [[PX153 - D2 - solving 2nd order homogeneous ODEs|2nd order homogeneous ODE]]: $$v(t) = v(0)\exp\left(-\frac{t}{\tau}\right)$$
	- $\tau:$ typically slowing down (damping) time

- if there is external forcing, to maintain constant speed, $v:$ $$\vec F_{ext} = + IBL\,\hat x$$
- work done by the external force (per unit time), ie: power input: $$P = F_{ext}v = IBLv = \frac{B^{2}L^{2}}{R}v^{2}$$
- power dissipated due to ohmic heating: $$P_{loss}= RI^{2}= R \frac{B^{2}L^{2}}{R^{2}}v^{2} = \frac{B^{2}L^{2}}{R}v^{2}$$
$$P_{input} = P_{loss}$$
