$$\vec D_{r} = \epsilon_{0}\epsilon_{r}\vec E$$
	where, $\epsilon_{r}=$ relative permittivity
- $\epsilon_{r} \geq 1$ 
- dimensionless: constant of the material
- permittivity of a material: $\epsilon = \epsilon_{r}\epsilon_{0}$
- also, $$\begin{align*}
\vec P &= \vec D - \epsilon_{0}\vec E \\
&= \epsilon_{0}\epsilon_{r}\vec E - \epsilon_{0}\vec E \\
&= (\epsilon_{r}-1)\epsilon_{0}\vec E \\
&= \chi_{e}\epsilon_{0}\vec E
\end{align*}$$
	where, $\chi_{e} = (\epsilon_{r}-1)$
- $\vec P$ obeys a [[PX157 - B5a - gauss's law|gauss's law]] for *bound* charges: $$\newcommand{\oiint}{\subset\!\supset \!\!\!\!\!\!\!\!\!\!\iint} \oiint_{S} \vec P \cdot d\vec S = -Q_{encl,b.}$$
- for all charges: $$\begin{align*}
	\epsilon_{0} \oiint_{S} \vec E\cdot d\vec S &= Q_{encl} \\
	&= Q_{encl,f.} + Q_{encl,b.} \\
	&= Q_{encl,f.}- \oiint_{S}\vec P \cdot d\vec S
\end{align*}$$
- $\vec D$ obeys a [[PX157 - B5a - gauss's law|gauss's law]] for *free* charges: $$\oiint_{S}(\epsilon_{0}\vec E + \vec P)\cdot d\vec S = \oiint_{S} \vec D\cdot d\vec S = Q_{encl,f.}$$
- another way to define $\epsilon_{r}:$ $$\epsilon_{r} = \frac{C}{C_{0}}$$
	where, $C$ and $C_{0}$ are the capacitances with and without the material
- for plate capacitor: $$C_{0} = \frac{\epsilon_{0}A}{d}, \; C = \frac{\epsilon A}{d}=\epsilon_{r}C_{0}$$
![[Pasted image 20240207103041.png]]

| $C_{0}= \frac{\epsilon_{0}A}{d}$                        | $C = \epsilon_{r}C_{0}$                                                     |
| ------------------------------------------------------- | --------------------------------------------------------------------------- |
| $V_{0}= \frac{Q}{C_{0}}$                                | $V= \frac{Q}{C} = \frac{Q}{\epsilon_{r}C_{0}} = \frac{V_{0}}{\epsilon_{r}}$ |
| $E_{0} = \frac{\sigma}{\epsilon_{0}} = \frac{V_{0}}{d}$ | $E = \frac{E_{0}}{\epsilon_{r}}$                                            |
| $U_{0} = \frac{1}{2} \frac{Q^{2}}{C_{0}}$               | $U = \frac{1}{2} \frac{Q^{2}}{C} = \frac{U_{0}}{\epsilon_{r}}$              |
| $u_{0} = \frac{1}{2}\epsilon_{0}E_{0}^{2}$              | $u = \frac{1}{2}\epsilon_{r}\epsilon_{0}E^{2} = \frac{v_{0}}{\epsilon_{r}}$ |
