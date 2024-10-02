## equipotential surfaces
- surfaces of constant potential
- from *[[PX157 - B8a - calculating potentials#^7d6a9f|here]]*: $$\therefore V_{a}-V_{b} = \int_{a}^{b}\vec E \cdot d\vec l$$
- assume that the points, $a$ and $b$, are infinitesimally close: $$\therefore V_{a}-V_{b} = \vec E \cdot d\vec l$$
- assume that the points, $a$ and $b$ lie on the same equipotential surface: $$V_{a} = V_{b} \implies \vec E \cdot d\vec l = 0 \implies \vec E \perp d\vec l$$
- $d\vec l$ is tangential to the equipotential surface. hence, **$\vec E$ is perpendicular to the equipotential surface**
![[Pasted image 20240129155351.png]]
- in a conductor, $\vec E = 0$, and $V = constant \implies$ equipotential volume
![[Pasted image 20240129155417.png]]
## potential gradients
- from *[[PX157 - B8a - calculating potentials#^7d6a9f|here]]*: $$\begin{align*}
	V_{a}-V_{b} &= \int_{a}^{b}\vec E \cdot d\vec l \\
	V_{a}-V_{b} &= -\int_{b}^{a} dV \\
	\therefore \int_{a}^{b}[\vec E\cdot d\vec l + dV] &= 0
\end{align*}$$
- this is true also if $a$ and $b$ are infinitesimally close: $$\begin{align*}
	\vec E \cdot d\vec l + dV &= 0 \\
	dV &= -\vec E \cdot d\vec l
\end{align*}$$
- in $1$D: $$dV = - \vec E_{x}d\,x \implies E_{x}= - \frac{dV}{dx}$$
- in $3$D: $$\begin{align*}
dV = - \vec E \cdot d\vec l &= -E_{x}dx -E_{y}dy - E_{z}dz \\
&= \frac{\partial V}{\partial x}dx + \frac{\partial V}{\partial y}dy + \frac{\partial V}{\partial z}dz \\
\end{align*}
$$
- $\vec r = x\hat x + y\hat y + z\hat z$, and ${} d\vec l = d\vec r = dx \hat x + dy\hat y + dz\hat z {}$
$$\vec E = -\left(\frac{\partial V}{\partial x}\hat x + \frac{\partial V}{\partial y}\hat y + \frac{\partial V}{\partial z}\hat z\right) \equiv  - \vec\nabla V$$

- eg: a ring of charges
	$$V(x,0,0) = \frac{Q}{4\pi\epsilon_{0}\sqrt{x^{2}+ a^{2}}}$$
	$$\vec E(x,0,0) = -\vec\nabla V = -\left(\frac{\partial V}{\partial x}\hat x + \frac{\partial V}{\partial y}\hat y + \frac{\partial V}{\partial z}\hat z\right)$$
	- $\frac{\partial V}{\partial y} =0$ and $\frac{\partial V}{\partial z}=0$ because expect an *extremum* (minimum/maximum) on x-axis
	$$\begin{align*}
	\vec E (x,0,0) &= - \frac{Q}{4\pi\epsilon_{0}} \left(- \frac{1}{2}\right) \frac{2x}{(x^{2}+a^{2})^{\frac{3}{2}}} \, \hat x \\ 
	&= \frac{Q}{4\pi\epsilon_{0}} \frac{x}{(x^{2}+a^{2})^{\frac{3}{2}}} \hat x
\end{align*}$$

## potential of an ideal dipole
$$V(r) = \frac{\vec p \cdot \hat r}{4\pi\epsilon_{0}r^{2}} = \frac{\vec p \cdot \vec r}{4\pi\epsilon_{0}r^{3}}$$
$$\vec E = -\vec\nabla V = -\frac{1}{4\pi\epsilon_{0}} \left[(\vec p\cdot\vec r)\vec\nabla \left(\frac{1}{r^{3}}\right) + \frac{1}{r^{3}} \vec\nabla (\vec p\cdot\vec r) \right]$$
$$\begin{align*}
\vec\nabla \left(\frac{1}{r^{3}}\right) &= - \frac{3}{r^{4}}\vec\nabla r \\
&= \frac{-3}{r^{4}} \vec\nabla\sqrt{x^{2}+y^{2}+z^{2}} \\
&= - \frac{3}{r^{4}} \frac{1}{2\sqrt{x^{2}+y^{2}+z^{2}}} \vec\nabla(x^{2}+y^{2}+z^{2}) \\
&= - \frac{3}{2r^{5}} (2x \vec\nabla x + 2y \vec\nabla y + 2z \vec\nabla z) \\
&= - \frac{3}{r^{5}} (x\hat x +y\hat y+z\hat z) \\
&= - \frac{3}{r^{5}} \vec r \\
\therefore \vec\nabla \left(\frac{1}{r^{3}}\right)&=  - \frac{3}{r^{4}}\hat r
\end{align*}$$
$$\vec\nabla (\vec p \cdot \vec r ) = \vec\nabla (p_{x}x + p_{y}y + p_{z} z) = p_{x} \hat x + p_{y} \hat  + p_{z} \hat z = \vec p$$
$$\begin{align*}
\vec E = -\vec\nabla V &= -\frac{1}{4\pi\epsilon_{0}} \left[ (\vec p\cdot\vec r)(- \frac{3}{r^{4}}\hat r) + \frac{1}{r^{3}} \vec p \right] \\
&= \frac{1}{4\pi\epsilon_{0}r^{3}} \left[3(\vec p\cdot\hat r)\hat r - \vec p \right]
\end{align*}$$
