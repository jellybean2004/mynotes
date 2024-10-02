 ![[Pasted image 20240305183804.png]]
$$V(x) = \begin{cases}
\infty & for & x<0,\; x>L \\
0 & for & 0\leq x\leq L
\end{cases}$$
- [[PX156 - D1 - time independent schrodinger equation|TISE]]: $$- \frac{\hbar^{2}}{2m} \frac{d^{2}\phi}{dx^{2}} + V\phi = E\phi$$
- to avoid infinite energies (to make sure the particle doesn't exist outside the well): $\phi(x=0)$ for $x<0$, $x>L$
- for $0\leq x\leq L$, as $V(x)=0:$ $$\begin{align*}
		- \frac{\hbar^{2}}{2m} \frac{d^{2}\phi}{dx^{2}} &= E\phi \\
		\frac{d^{2}\phi}{dx^{2}}+k^{2}\phi &= 0
	\end{align*}$$
	where, $k^{2}= \frac{2mE}{\hbar^{2}}$
- trial solution: $\phi=A\sin(kx)+B\cos(kx):$ $$\frac{d^{2}\phi}{dx^{2}}= -Ak^{2}\sin(kx)-Bk^{2}\cos(kx) = -k^{2}\phi$$
- using the boundary conditions to find the constants:
	$\phi=0$ at $x=0 \implies B=0$
	$\phi=0$ at $x=L \implies A\sin(kL)=0 \implies k = \frac{n\pi}{L},\;n\in\mathbb{Z}$
- $$\phi(x) = A\sin\left(\frac{n\pi x}{L}\right)$$
- using normalizing conditions: $$1 = \int_{0}^{L} A^{2}\sin^{2}\left(\frac{n\pi x}{L}\right)\,dx =\dots\implies A = \left(\frac{2}{L}\right)^{\frac{1}{2}}$$
- the normalized function: $$\phi = \sqrt\frac{2}{L} \sin\left(\frac{n\pi x}{L}\right)$$
- the energy levels: $$E_{n} = \frac{\hbar^{2}k^{2}}{2m} = \frac{\hbar^{2}n^{2}\pi^{2}}{2mL^{2}}$$
![[Pasted image 20240305185217.png]]
- examples:
	- semiconductor quantum well
	- carotenes (conjugated polyenes)
	- conductance quantization in nanowires
