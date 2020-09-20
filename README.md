# Kinetic locking

Data analysis procedures for the kinetic locking detection scheme.
Kinetic locking is a scheme for single-molecule micro-manipulation that consists of a fluctuating DNA probe that is affected by the binding of on other nucleic acid or of a protein. 
Detection is obtained by looking at the evolution of the distribution of the times spent in the open and closed states as a function of the concentration of the other species.
The files presetend here contain the procedures used to infer the binding kinetics from the list of times spent in the open and closed states of the probe.

**Kinetic_lock_DeltaG.ipynb** contains the procedures allowing us to measure the free energy of binding.
**Kinetic_lock_multifit.ipynb** contains the procedures allowingus  to measure the binding parameters kon and koff separately.

All error estimations on the inferred parameters are based on bootstrap resampling.

