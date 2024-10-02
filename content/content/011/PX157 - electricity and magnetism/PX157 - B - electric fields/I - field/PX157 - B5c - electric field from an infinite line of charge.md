$$\lambda = \frac{\Delta Q}{\Delta L} \to constant$$
![[Pasted image 20240117160026.png]]
- **step 1: symmetry**
	- $\vec E$ points radially outwards in a cylindrical sense (away from the axis), ie: $\vec E = E \, \hat R$
	- $|\vec E|$ is constant on a cylindrical shell concentric with the line of charge
- **step 2: gaussian surface**
	- cylinder of radius, $R$, and length, $L$
	- **key point**: the cylindrical shell is still open, two circles are needed at the top and the bottom to create an enclosed shell
	$$\newcommand{\oiint}{\subset\!\supset \!\!\!\!\!\!\!\!\!\!\iint}
	\oiint \vec E \, d\vec S = \iint_{top} \vec E \, d\vec S + \iint_{bottom}\vec E \, d\vec S + \iint _{curled} \vec E \, d\vec S$$
		- top: 
			$\vec E = E \, \hat R$
			$d\vec S = dS \, \hat z$
			$\vec E \cdot d\vec S = E \, dS \, \hat R \, \hat z = 0$
		- bottom: 
			$\vec E = E \,\hat R$ 
			$d\vec S = -dS \, \hat z$
			$\vec E \cdot d\vec S = -E \, dS \, \hat R \, \hat z = 0$
		- curved: 
			$\vec E = E \,\hat R$ 
			$d\vec S = dS \, \hat R$
			$\vec E \cdot d\vec S = -E \, dS \, \hat R \, \hat R = E \, dS$
		$$\therefore \;\oiint \vec E \cdot d\vec S = \iint_{curved}E \, dS = E \, 2\pi R L$$
- **step 3:** $$Q_{encl.}=\lambda L$$
- **step 4:** $$E \, 2\pi RL = \lambda \frac{L}{\epsilon_{0}} \implies \vec E = \frac{\lambda}{2\pi\epsilon_{0}R}\hat R$$

