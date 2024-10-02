## definition
- adding up. eg: area under a curve, volume inside a surface, work done from $A$ to $B$, total electric flux across a surface

- inverse of differentiation
- if $F(x) = \int^{x} f(x').dx'$, where, $A\to$ some reference point
$$\begin{align}
	F'(x) &= \lim_{\delta x \to 0} \frac{F(x+\delta x)-F(x)}{\delta x} \\
	&= \lim_{\delta x \to 0} \frac{\int_{A}^{x+\delta x} f(x').dx' - \int_{A}^{x} f(x').dx'}{\delta x} \\
	&= \lim_{\delta x \to 0} \frac{\int_{A}^{x+\delta x} f(x').dx' + \int_{x}^{A} f(x').dx'}{\delta x} \\
	&= \lim_{\delta x \to 0} \frac{\int_{x}^{x+\delta x} f(x').dx' }{\delta x} \\
	&= \lim_{\delta x\to0} \frac{f(x')\delta x}{\delta x} \\
	&= f(x)
\end{align}$$
## a bit of maths analysis
- maths behind differentiation and integration is called analysis and concerned with limits
- differentiation, ie: $$lim_{\delta x\to0} \frac{f(x+ \delta x)-f(x)}{\delta x} \stackrel{?}{=} f'(x)$$A
- integral, ie: $$\lim_{N\to\infty} \sum\limits_{n=0}^{N}f\left(x_{A} + n\frac{x_{B}-x_{A}}{N}\right)\frac{x_{B}-x_{A}}{N} \stackrel{?}{=} \int_{x_{A}}^{x_{B}}f(x').dx'$$
a) **riemann integral**
	![[Pasted image 20240110183649.png]]
- let $A=$ area under the curve (between $0$ and $a$): $$A \approx \sum\limits_{i=0}^{N-1} f(x_{i})(x_{i+1}-x_{i}) $$
- if the limit $N\to \infty$ exists: $$\lim_{N\to\infty}\sum\limits_{i=0}^{N-1} f(x_{i})\Delta x_{i} = \int_{0}^{a} f(x').dx'$$
- we will work with *riemann integral
- assume that all functions of interest are integrable
- assume that we cab interchange order of integration in multiple integrals (*fabini's theorem*)

- **key points**:
	- integration by parts: $$
	  \begin{align}
	  \int_{a}^{b} u \frac{dv}{dx}.dx & = \int_{a}^{b} \frac{d(uv)}{dx}. dx - \int_{a}^{b}v \frac{du}{dx}.dx \\
	  &= [uv]_{a}^{b}-\int_{a}^{b} \frac{du}{dx}v.dx
	  \end{align}$$
	- substitutions: $$ I = \int \frac{1}{(1-x)^{\frac{1}{2}}}.dx$$
		- let $x= \sin u$ , and $dx = \cos u .du$ : $$I = \int \frac{\cos u.du}{\cos u} = \int du = u = \sin^{-1} x$$
	- partial fractions: $$\int \frac{1}{1-x^{2}}.dx = \int \frac{1}{2}\left(\frac{1}{1-x}+ \frac{1}{{1+x}}\right)= \frac{1}{2} ln((1-x)(1+x))$$