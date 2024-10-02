![[Pasted image 20231030184750.png]]
- model motion of our oscillator through a viscous fluid with a drag force proportional to $\dot x$, ie:$-b\dot x$
	- [[PX155 - A2 - newton's second law]]: $m \ddot x = -kx - b\dot x$
	- dividing by m on both sides:$$\ddot x + \omega^{2}x + \gamma \dot x =0$$
			where, $\gamma = \frac{b}{m}$
	- switch to complex notation: $$\ddot z + \omega ^{2}z + \gamma \dot z = 0 \, ...[1]$$
	- physically motivated: $$z = ae^{pt}$$
			where, $p$ might be complex
		- $p$ is imaginary - oscillation
		- $p$ is real and negative - decay
			$z=ae^{pt}$
			$\dot z = pae^{pt}=pz$
			$\ddot z = p^{2}ae^{pt}=p^2z$
			- in $[1]$: $p^{2}z+\omega ^{2}z+\gamma pz =0$
				$z(p^{2} + \gamma p + \omega^{2})=0$
				$either \; z=0$ boring
				$or \; p^{2} + \gamma p + \omega^{2} = 0$
					$$p = \frac{-\gamma\pm\sqrt{\gamma^{2}-4\omega^{2}}}{2}$$
					$$p=- \frac{\gamma}{2} \pm \sqrt{\left(\frac{\gamma}{2}\right)^{2}-\omega^{2}}$$
				- $p$ can be complex, or real and negative *but* never real and positive