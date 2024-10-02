
![[Pasted image 20240207180739.png]]
## charging a capacitor:
- at $t=0:$ 
	- capacitor is not charged
	- the circuit is closed: $$\begin{align*}
		I_{0} = \frac{V_{ab}}{R} &= \frac{\epsilon}{R} \\\\
		Q_{0} &= 0 
	\end{align*}$$
- at $t=t':$
	- from [[PX157 - B14a - circuits - kirchhoff's rules#kirchhoff's loop rule|kirchhoff's loop rule]]: $$\begin{align*}
		\epsilon &= RI + \frac{Q}{C} \;, & I &= \frac{dQ}{dt}\\
		\epsilon &= R \frac{dQ}{dt}+ \frac{Q}{C}
\end{align*}$$
	- for $t\to\infty:$ the capacitor to be fully charged: $$\epsilon = V_{bc} = \frac{Q_{final}}{C} \implies Q_{final}= \epsilon C$$
	- solving a [[C - first order ODEs|first order ODE]] : try$Q(t) = \tilde Q (t) e^{- t/RC}:$ 
	$$\tilde Q(t) = \int_{0}^{t} \frac{\epsilon}{R} e^{- \frac{t'}{RC}}\,dt' = \epsilon C (e^\frac{t}{RC}-1)$$
	 $$\implies Q(t) = \epsilon C (1-e^{- \frac{t}{RC}})$$
	$$I(t) = \frac{dQ}{dt}= \frac{\epsilon}{R} e^{- \frac{t}{RC}}$$
![[Pasted image 20240213093241.png]]
![[Pasted image 20240213093331.png]]

- typical rate of charging is given by the *time constant*, or the *relaxation time* : $$\tau = R\,C$$
## discharging a capacitor
- at $t=0:$
	- the battery is disconnected 
	- $I_{0}=0$, $Q_{0}=\epsilon C$
	- [[PX157 - B14b - circuits - maxwell loops|loop rule]]: $$\begin{align*}
			RI + \frac{Q}{C} &= 0 \\
			R \frac{dQ}{dt} + \frac{Q}{C} &= 0
		\end{align*}$$
	- solving the [[C - first order ODEs]] : $$\begin{align*}
			Q(t) &= Q_{0}e^{-\frac{t}{RC}} \\
			&= \epsilon C e^{-\frac{t}{RC}}
		\end{align*}$$
	- current: $$I(t) = \frac{dQ}{dt} = - \frac{\epsilon C}{RC} e^{-\frac{t}{RC}} = -\frac{\epsilon}{R} e^{-\frac{t}{RC}}$$
![[Pasted image 20240213093148.png]]
![[Pasted image 20240213093204.png]]
