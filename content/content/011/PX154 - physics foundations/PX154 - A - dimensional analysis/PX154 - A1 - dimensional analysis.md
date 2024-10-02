## units
- [SI units](https://www.npl.co.uk/si-units)
- for energy, we will sometimes use the electron volt - 
$$ 1 eV = 1.6 \times 10^{-19}J $$
	- visible light photon ~ 1.8-3.1 eV
	- room temperature ~ 25 meV 
- distances
	- $1 \; angstorm \equiv 10^{-10}m$
	- parsec = 3.26 \; light years \; (3.1 \times 10^{16} m)  
## units and dimensions

- thought experiment :
	- playing on a swing
		- me : 80 kg
		- friend : 60 kg
	- who swings faster?
		- let us consider a simple pendulum
			- attached to a pivot by a massless string at an angle theta
			- to find: the period of the pendulum (T)
			- could be a function of length (l), mass of the person (m), gravity (g)
			- assumptions + approximations are made
			$$T = f(l,m,g)$$
			- we could invoke mechanics... or...
				- T (LHS) has units of seconds
				- RHS must have a unit of seconds
				- *units must match on both sides of the equation*
					- it looks like we have kg on RHS
					- for length, we can see that we try 
					$$\frac{l}{g} = \frac{m}{ms^{-2}} = s^{2}$$
					- take: $\sqrt{l \over g} = s$
					- we will end up with: $$T = 2 \pi \sqrt{l \over g} $$
						- $2\pi$ was not determined by dimensional analysis
						- it is a constant with no units
					- we can write this as: $$2\pi = T\sqrt{g\over l}$$
						- $2\pi$ is a constant with no units 
						$\therefore T\sqrt{g\over l}$ must also be a constant with no units
						- this is not true for all consistent sets of units 
						$\implies$ motivates us to introduce dimensions
