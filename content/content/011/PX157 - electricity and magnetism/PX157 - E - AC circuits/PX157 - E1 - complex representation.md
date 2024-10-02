$$V(t) = V_{0}\cos(\omega t)$$
	$\omega=$ angular frequency $=2\pi f$
![[Pasted image 20240311182013.png]]
### [[PX153 - B2 - polar representation|polar representation of a complex number]]
![[Pasted image 20240311182102.png]]
$$z = x+iy = re^{i\theta}$$
	$r=\sqrt{x^{2}+y^{2}}$
	$\theta=\arctan(\frac{y}{x})$
- here, $\theta=\omega t:$ $$z= re^{i\omega t} = r(\cos(\omega t)+ i\sin(\omega t))$$
- the physical solution is $\mathbb Re(z)$

- notation: 
	- real voltage: $V =V_{0}\cos(\omega t)$
	- complex representation: $\tilde V = V_{0}e^{i\omega t}$
	- '$j$' is used instead of '$i$', $j=\sqrt{-1}$

- *phasor* ($\tilde V$): $$V(t) = V_{0}\cos(\omega t) \to \tilde V = V_{0}e^{j\omega t}$$
- phase differences: $$\begin{align*}
		V_{1} &= V_{0}\cos(\omega t) \\
		V_{2} &= V_{0}\cos(\omega t+\phi) \\
	\end{align*}$$
![[Pasted image 20240311182126.png]]- $V_{2}$ leads $V_{1}$ by a phase difference, $\phi$
![[Pasted image 20240311182139.png]]
- in complex notation: $$\begin{align*}
		\tilde V_{1} &= V_{0}e^{j\omega t} \\\\
		\tilde V_{2} &= V_{0}e^{j\omega t+j\phi} \\
		 &= \tilde V_{1}e^{j\phi}
	\end{align*}$$
- eg: $\tilde V_{2}= \tilde V_{1} e^{j \frac{\pi}{2}} = j\tilde V_{1}$
![[Pasted image 20240311182211.png]]
### magnitudes
$\tilde z = x + jy$
$|\tilde z| = \sqrt{x^{2}+y^{2}}$

$\tilde z = \frac{\tilde z_{1}}{\tilde z_{2}}$
$|\tilde z| = \frac{|\tilde z_{1}|}{|\tilde z_{2}|}$
