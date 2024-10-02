[[PX153 - E3 - driven damped simple harmonic motion]]
- add an additional oscillatory force $F=F_{0}\cos\omega t$ to the damped mass on a spring, where $\omega =$ *applied* frequency
- [[PX155 - A2 - newton's second law]]: $m\ddot x = -kx -b \dot x+F_{0}\cos \omega t$
	- dividing by $m$ and switching to complex notation:
		$\ddot z + \gamma \dot z + \omega_{0}^{2}z = \frac{F_{0}}{m}e^{i\omega t}...[1]$
	- note: $\omega_{0}=\sqrt{\frac{k}{m}}$, $\omega$ is the frequency of the applied oscillating force
- we care about long term solutions, after damped SHM solutions have died away
- try: $z=ae^{i\omega t}$
		$\dot z = i\omega z$
		$\ddot z = -\omega^{2}z$
- in [1] : $-\omega^{2}z + i \omega \gamma z + \omega_{0}^{2}z = \frac{F_{0}}{m}e^{i\omega t}...[1]$ 
		$(-\omega^{2} + i \omega \gamma + \omega_{0}^{2})ae^{i\omega t} = \frac{F_{0}}{m}e^{i\omega t}$
		$a = \frac{F/m}{(\omega_{0}^{2}-\omega^{2}) + i \omega \gamma}$ this is a complex number
- recall $a=|a|e^{i\phi}$ in modulus argument form
		$z = |a|e^{i(\omega t+\phi)}$
	- with $x= \mathbb Re (z) = |a|\cos(\omega t+\phi)$
- equate two forms of $a$: $$\frac{F/m}{(\omega_{0}^{2}-\omega^{2}) + i \omega \gamma}= |a|e^{i\phi}$$
- B2: ${} |a| = \frac{F/m}{\sqrt{(\omega_{0}^{2}-\omega^{2})^{2} - (\omega \gamma)^{2}}} {}$ , $\tan\phi = \frac{-\gamma\omega}{\omega_{0}^{2}-\omega^{2}}$
-
- comparison: consider a *static* load ($W=0$)
		$|a|_{0} = \frac{F_0/m}{\omega_{0}^{2}} = \frac{F_{0}}{k}$
	- $|a|_0$ is an extension of spring under static load: $$\frac{|a|}{|a|_{0}}= \frac{\omega_{0}^{2}}{\sqrt{(\omega_0^2-\omega^{2})+(\gamma\omega)^{2}}}$$
	- for small $\omega_{0}-\omega$ and small $\gamma$, we can have $\frac{|a|}{|a|_{0}}>1$, so, large amplitude and static load
- key features: 
	- amplitude of the response varies with $\omega$ and peaks close to $\omega_{0} \implies$ *resonance*
	- 
		- at small $\omega$, system responds in phase($\phi=0$)
		- at $\omega=\omega_{0}, \phi=-90\degree$  
		- at large $\omega, \phi=-180\degree$  - "antiphase"
	- ![[Pasted image 20231113085934.png]]
		- FWHM - full width at half maximum - width of resonance
		- $FWHM \approx \gamma$
	- dimensionless Q-factor is $\omega_0/FWHM$, so, $\approx \omega_0/\gamma$