$$(\cos{\theta}+i\sin{\theta})^n=\cos{n\theta}+i\sin{n\theta}$$
- follows from [[PX153 - B2 - polar representation#^775224|euler's formula]] and leads to $$z^n=r^ne^{in\theta}=r^n(\cos{n\theta+i\sin{n\theta})}$$
	- valid for $n\in \mathbb Z$
## solving polynomials
- the total number of roots = largest power
- let's write the roots of an nth order polynomial as $z_k$, where $k=0,1,2...(n-1)$ and take a polynomial of the form $z^n_k=A^{-\mathbb{Z}}$
		$A=re^{i\theta}e^{i2\pi k}$
			$e^{i2\pi}=1$ and, $e^{i2\pi k}=1^k=1$
		$A^\frac{1}{n}=z_k=r^{\frac{1}{n}}e^{i\frac{\theta}{n}}e^{i\frac{2\pi k}{n}}$
			if $k=0$: $z_0=r^{1/n}e^{i\theta/n}$
			if $k=1$: $z_1=r^{1/n}e^{i\theta/n}e^{i2\pi/n}=z_0e^{i2\pi/n}$
			...
			if $k=n-1$: $z_{n-1}=r^{1/n}e^{i\theta/n}e^{i(n-1)2\pi/n}$$$z_n=z_0e^{ik2\pi/n}=z_0e^{i2\pi}=z_0$$
				n roots from $k = 0$ to $k=n-1$
- eg: solve $z^4-1=-i\sqrt{3}$
	- ![[Pasted image 20231016144508.png]]
- eg: solve $z^3-(2-2i)z=9$
- eg: solve $z^4-(2-2i)z^3-(2+2i)z+8=0$