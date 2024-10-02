- particles can decay to different final states with different characteristic decay rates, $\Gamma_{i}$
- each different final state is called a '*channel*'
- each $\Gamma_{i}:$ 'partial decay rate'
- the total decay rate: $$\Gamma = \sum\limits_{i}\Gamma_{i}$$
- to understand which decay channels dominate in a particle's decay scheme, the *branching fraction* is used

## branching fraction
- *branching fraction*: for a given channel, $i$, its branching fraction is: $$BF(i) = \frac{\Gamma_{i}}{\sum\limits_{i}\Gamma_{i}}$$ #imp
- AKA *branching ratio*
$$\begin{align*}
	BF(\pi^{0}\to\gamma+\gamma) &=  0.9998 \\ 
	BF(\pi^{0}\to\gamma+e^{-}+e^{+}) &=  0.0001 \\
	\vdots \hspace{20mm} &<0.0001
\end{align*}$$
- eg: what is $BF(Z^{0}\to\nu\bar\nu)?$
	- assuming $\Gamma(X^{0}\to l\bar l) = \Gamma(Z^{0}\to q\bar q) = \Gamma(Z^{0}\to \nu\bar\nu)$
	$$BF(Z^{0}\to \nu\bar\nu) = \frac{\Gamma_{i}(Z^{0}\to\nu\bar\nu)}{\Gamma_{tot}}$$
	- numerator: since there are 3 different flavours of neutrinos: $$\Gamma_{i}(Z^{0}\to\nu\bar\nu) = 3\Gamma(Z^{0}\to\nu_{e}\bar\nu_{e})$$
	- denominator: $$\Gamma_{tot}= \sum\limits_{i=1}^{N}\Gamma_{i} = N\Gamma(Z^{0}\to\nu_{e}\bar\nu_{e})$$
	- what is $N$?
		- $\Gamma(Z^{0}\to l\bar l): 3: l=e,\mu,\tau$
		- $\Gamma(Z^{0}\to \nu\bar\nu): 3: \nu_{x},\,x=e,\mu,\tau$
		- $\Gamma(Z^{0}\to q\bar q):$ 
			- $m(Z^{0})<<2m_{top}\implies$ ignore top  
			- no flavour changing neutral currents 
			- $q=u,d,s,c,b$
			- quark channels: $5\times$number of colours $=15$
	$$\begin{align*}
			BF(Z^{0}\to \nu\bar\nu) &= \frac{3\Gamma(Z^{0}\to\nu_{e}\bar\nu_{e})}{N\Gamma(Z^{0}\to\nu_{e}\bar\nu_{e})} \\
			&= \frac{3}{N} \\
			&= \frac{3}{3+3+15} \\
			&= \frac{1}{7}
		\end{align*}$$
