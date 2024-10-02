![[Pasted image 20240125100545.png]]
$$\vec E(x_{p},0,0) = \frac{Qx_{p}}{4\pi\epsilon_{0}(x_{p}^{2}+a^{2})^{\frac{3}{2}}} \hat x$$
- let, $\hat r = x\,\hat x \implies d\vec l = dx\,\hat x$ 
$$\begin{align*}
\int_{a}^{b}\vec E\cdot d\vec l &= \frac{Q}{4\pi\epsilon_{0}}\int_{x_{p}}^{x_{b}} \frac{x}{(x^{2}+a^{2})^{\frac{3}{2}}}dx \\
V_{a}-V_{b} &= \frac{Q}{4\pi\epsilon_{0}} \frac{1}{\sqrt{x_{p}^{2}+a^{2}}} \bigg|_{x_{p}}^{x_{b}}\\
	&= \frac{Q}{4\pi\epsilon_{0}} \left[\frac{1}{\sqrt{x_{b}^{2}+a^{2}}} - \frac{1}{\sqrt{x_{p}^{2}+a^{2}}}\right] \\
\end{align*}$$
- define: $V(b\to\infty)=0$: $$\therefore V_{a}= \frac{Q}{4\pi\epsilon_{0}} \frac{1}{\sqrt{x_{p}^{2}+a^{2}}}$$
### alternative approach
- consider section with charge $dQ$, and treat it as a point charge: $$dV_{p} = \frac{dQ}{4\pi\epsilon_{0}\sqrt{x_{p}^{2}+a^{2}}}$$
- for all sections: $$\int dV_{p} = V_{p} = \frac{Q}{4\pi\epsilon_{0}\sqrt{x_{p}^{2}+a^{2}}}$$