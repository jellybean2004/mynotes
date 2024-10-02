$$V(x) = \begin{cases} 
    V_{0} & for & x<0,x>L \\
    0 & for & 0\leq x\leq L
\end{cases}$$
- [[PX156 - D1 - time independent schrodinger equation|TISE]]: $$- \frac{\hbar^{2}}{2m} \frac{d^{2}\phi}{dx^{2}} + V\phi = E\phi$$
- it is no longer true that $\phi(x)=0$ for $x<0,x>L$, ie: particle can exist outside the well
- inside the well, $V=0$: $$\frac{d^{2}\phi}{dx^{2}}+k^{2}\phi=0$$
	where, $k^{2}=\frac{2mE}{\hbar^{2}}$
- outside the well: $$\begin{align*}
		- \frac{\hbar^{2}}{2m} \frac{d^{2}\phi}{dx^{2}} + V_{0}\phi &= E\phi \\
		\frac{d^{2}\phi}{dx^{2}} - \frac{2m}{\hbar^{2}}(V_{0}- E)\phi &= 0 \\
		\frac{d^{2}\phi}{dx^{2}} - \alpha^{2}\phi &= 0		
	\end{align*}$$
	where, $\alpha^{2}=\frac{2m}{\hbar^{2}}(V_{0}- E)$
	- no analytical solution
- the wavefunctions inside and outside need to match so that the boundary conditions are satisfied
- $\phi(x)$ and $\frac{d\phi(x)}{dx}$ must be continuous at the boundary points, $x=0,L$

![[Pasted image 20240305190517.png]]
![[Pasted image 20240305190528.png]]
