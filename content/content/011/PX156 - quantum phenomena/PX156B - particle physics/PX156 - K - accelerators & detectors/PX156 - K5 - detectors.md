- collider detectors are onion-like with different types of sub detectors with different types of subdetectors doing different things to 'reconstruct' particles coming from a collision
## tracker 
- detects and tracks charged particles close to the interaction point
- many type of trackers
- all are built in layers around the beam pipe to trace particles coming out

![[Pasted image 20240515122943.png]]

## calorimeter
- energy measurement
### electromagnetic calorimeter (ECAL) 
- measures electron and photon energies from how they move through material
- electrons: in a field of an atom in a material, it scatters, radiating in a photon
- photons: pair-production
- in a detector, an electromagnetic shower of $e^{-}/e^{+}/\gamma$ is created
- $\gamma$ can be detected in light detectors
### hadronic calorimeters (HCAL)
- same thing a ECAL for hadrons
- instead of just $e^{-}/e^{+}/\gamma$, there are also other hadrons in the shower

## probability of survival 
- calorimeters are designed around specific length scales that define the shower development
- EM showers: probability that an electron or photon survives to a distance, $x$, inside a material as: $$P_{e}(x) = \exp\left(- \frac{x}{x_{0}}\right)$$
	where, $x_{0}=$ reiteration length, property of a material 
- hadronic showers: probability of a hadron to survive a distance, $x$, inside a material as: $$P_{h}(x) = \exp\left(- \frac{x}{\lambda_{I}}\right)$$
	where, $\lambda_{x}=$ 'nuclear reiteration length', material dependent

| material | $x_{0}(cm)$ | $\lambda_{I}(cm)$ |
| :------: | :---------: | :---------------: |
|  water   |    $3.6$    |       $83$        |
|   iron   |    $1.8$    |       $17$        |
|   lead   |    $0.5$    |       $17$        |
