- a second order, linear, inhomogeneous ODE: $$a_{2}(x) \frac{d^{2}y}{dx^{2}} + a_{1}(x) \frac{dy}{dx}+ a_{0}(x)y(x)=f(x)$$
- *GS* will have 2 constants of integration, so, we will need 2 boundary conditions
- two steps: 
	- *step 1:* find the *GS* to the *complementary equation* - the homogenous version with $f(x)=0$
		- this gives $y_c(x)$ the complementary function: $$a_{2}(x) \frac{d^{2}y_{c}}{dx^{2}} + a_{1}(x) \frac{dy_{c}}{dx}+ a_{0}(x)y_{c}=0$$ which will have 2 constant s of integration
	- *step 2:* find the *particular integral* - any solution to the full ODE - ie: any $y_{p}(x)$: $$a_{2}(x) \frac{d^{2}y_{p}}{dx^{2}} + a_{1}(x) \frac{dy_{p}}{dx}+ a_{0}(x)y_{p}=f(x)$$ with no arbitrary constants
	- the *GS* is $y(x)=y_{c}(x)+y_{p}(x)$
	$$a_{2}(x) \frac{d^{2}y}{dx^{2}} + a_{1}(x) \frac{dy}{dx}+ a_{0}(x)y(x)= (a_{2}(x) \frac{d^{2}y_{c}}{dx^{2}} + a_{1}(x) \frac{dy_{c}}{dx}+ a_{0}(x)y_{c}) + (a_{2}(x) \frac{d^{2}y_{p}}{dx^{2}} + a_{1}(x) \frac{dy_{p}}{dx}+ a_{0}(x)y_{p})$$
	$$= 0 + f(x)$$