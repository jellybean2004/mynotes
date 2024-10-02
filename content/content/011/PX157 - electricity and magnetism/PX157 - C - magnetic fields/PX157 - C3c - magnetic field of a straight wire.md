![[Pasted image 20240218165659.png]] 
- using cylindrical coordinates, $(R,\phi,x):$ $$\begin{align*}
		\vec r' &= z'\,\hat z \\
		d\vec r' &= z'\,d\hat z \\
		\vec r &= R\,\hat R + z\,\hat z \\
		d\vec r' \times &(\vec r - \vec r') \parallel \hat \phi
\end{align*}$$
$$\begin{align*}
	\vec r -\vec r' &= R\,\hat R + (z-z')\hat z \\
	d\vec r' \times (\vec r -\vec r') &= dz'\,\hat z\times R\,\hat R + dz' \,\hat z \times (z-z')\hat z \\
	&= R\,dz'\,\hat\phi
\end{align*}$$
- from [[PX157 - C3b - the biot-savart law applied to a wire#^56411d|here]]: $$\begin{align*}
	d\vec B(\vec r) &= \frac{\mu_{0}}{4\pi} \frac{IR\,dz'}{|\vec r-\vec r'|^{3}} \hat\phi \\
	&= \frac{\mu_{0}}{4\pi} \frac{IR\,dz'}{|R^{2}+(z-z')^{2}|^{\frac{3}{2}}} \hat\phi
\end{align*}$$
- for all sections: $$\begin{align*}
	\vec B(\vec r) &= \frac{\mu_{0}I}{4\pi} \hat\phi \int_{-\infty}^{\infty} \frac{R}{(R^{2}+(z-z')^{2})^{\frac{3}{2}}}\,dz' \\
	&= \frac{\mu_{0}I}{4\pi R} \hat\phi \frac{-(z-z')}{\sqrt{R^{2}+(z-z')^{2}}} \Bigg|_{-\infty}^{+\infty}
\end{align*}$$
- taking the limits: $$\lim_{z'\to\pm\infty}\frac{(z-z')}{\sqrt{R^{2}+(z-z')^{2}}} = \lim_{z'\to\pm\infty} \frac{z'}{|z'|} =\pm1$$
$$\vec B(\vec r) = \frac{\mu_{0}I}{2\pi R} \hat\phi$$
