- there is an induced emf if there is no motion: $$\vec F = q\vec v\times \vec B = \vec 0$$
- but, [[PX157 - D1a - faraday's law|faraday's law]] still holds: $$\epsilon = - \frac{d\phi_{B}}{dt}$$
![[Pasted image 20240229222949.png]]
- eg: solenoid with current ($I_{s}(t)$), cross-sectional area ($A$), with $n$ turns pre unit length, and [[PX157 - C8 - solenoid|magnetic field]]: $$\vec B = \begin{cases}
        \vec 0  & outside \\
        \mu_{0}nI_{s}\,\hat z & inside
     \end{cases}$$
 - adding a *conducting* loop on the outside, [[PX157 - C1b - magnetic flux|magnetic flux]]: $$\phi_{B} = \iint_{S}\vec B \cdot d\vec S = \mu_{0}nI_{s}A$$
 - from [[PX157 - D1a - faraday's law|faraday's law]]: $$\epsilon = - \mu_{0} \frac{N}{L}A \frac{dI_{s}}{dt}$$
 - current induced in the loop: $$I_{w}= \frac{\epsilon}{R}= \frac{\mu_{0}NA}{LR} \frac{dI_{s}}{dt}$$
 - from [[PX157 - D1c - lenz's law|lenz's law]], the direction of $I_{w}$ is opposite to $I_{s}$

- the force acting on charge, $q$, is given by [[PX157 - C1a - the lorentz force|the lorentz force]]: $$\vec F = q (\vec E +\vec v \times \vec B)$$
- the emf is defined as: $$\epsilon = \oint_{loop} \frac{\vec F}{q}\cdot d\vec l$$
- since the wire is not moving, $\vec v=0$, and there is no external magnetic field, the only contribution can come from the electric field: $$\epsilon =\oint_{loop}\vec E\cdot d\vec l$$
- for stationary loops: $$\oint_{C}\vec E\cdot d\vec l = -\frac{d\phi_{B}}{dt}$$
- this poses a problem
- **remember**: in electrostatics, an electric field starts at a positive charge and ends at a negative charge
- $\int_{a}^{b}\vec E\cdot d\vec l$ represents the potential difference between the start and end points
- for a closed path, the start and the end points are the same, so the potential difference is zero, ie: ${} \oint_{C}\vec E \cdot d\vec l = 0$
- this is only valid in *time-independent* magnetic problems
- $\oint_{C}\vec E\cdot d\vec l\neq0:$ if there is a changing magnetic field
- $\phi_{B}$ generates closed loops of electric fields, called the *induced electric field*
- around a loop of induced electric field, since $\vec F=q\vec E$, the electric field does net work around a closed loop, and a potential can no longer be defined
- the concept of *electrostatic potential* no longer works

- solenoid's power output over the whole solenoid: $$P = |\epsilon|I = \left(\mu_{0} \frac{NA}{L} \frac{dI_{s}}{dt}\right) (I_{s} N) $$
- also, $$\begin{align*}
	B &= \mu_{0} \frac{N}{L}I_{s} \\
	\implies P &= BA \frac{dI_{s}}{dt}N \\
	&= \frac{LA}{\mu_{0}} B \frac{dB}{dt} \\
	\therefore P &= \frac{LA}{2\mu_{0}} \frac{dB^{2}}{dt} \\\\
	energy,\;U &= \int P\,dt = LA \frac{B^{2}}{2\mu_{0}} \\
	energy\,density,\; u &= \frac{U}{Vol.} = \frac{B^{2}}{2\mu_{0}}
\end{align*}$$
	- for electric field, [[PX157 - B11 - field energy#energy density of the electric field|energy density]], $u = \frac{1}{2}\epsilon_{0}E^{2}$

- comparing with $E=mc^{2}:$
	- hydrogen atom: 
		$Vol. = 6.2\times10^{-31}\,m^{3}$
		$B \approx 12.5\,T$
		$$U = \frac{B^{2}}{2\mu_{0}}Vol. = mc^{2}\implies m \approx 4.3\times10^{-40}\,kg$$

- **conclusion**:
	- **resistor**: dissipates energy
	- **capacitor**: stores energy in $\vec E$
	- **coil** (solenoid, inductor): stores energy in $\vec B$
