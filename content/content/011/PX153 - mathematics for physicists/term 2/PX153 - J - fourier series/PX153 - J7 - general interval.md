- a [[PX153 - J1 - introduction|fourier series]] is given by: $$f(x) = \frac{a_{0}}{2} + \sum\limits_{n=1}^{\infty}\left(a_{n}\cos\left(\frac{n\pi x}{L}\right) +b_{n}\sin\left(\frac{n\pi x}{L}\right) \right)$$ for $x \in [L,L)$
- from [[PX153 - J3 - proofs and derivations|proofs and derivations]]: $$\begin{align*}
		a_{n} &= \frac{1}{L} \int_{-L}^{L} f(x) \cos\left(\frac{n\pi x}{L}\right)\,dx \\
		b_{n} &= \frac{1}{L}\int_{-L}^{L} f(x) \sin\left(\frac{n\pi x}{L}\right)\,dx \\
		a_{0} &= \frac{1}{L}\int_{-L}^{L} f(x)\,dx
	\end{align*}$$

- for $a_{n}:$ $$\int_{-L}^{L} f(x)\cos \left[\frac{m\pi x}{L}\right] \,dx$$
![[Pasted image 20240205140754.png]]
