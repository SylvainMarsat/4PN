# 4PN
Post-Newtonian computations for non-spinning compact binaries at the 4PN order.

dynamics/ : dimreg potentials used for the 4PN Fokker action computation, together with PNComBin version and notebook

quadrupole/ : partial results for the dimreg potentials used for the 4PN quadrupole computation

## Nomenclature for the asymptotic expansion of potentials
Files starting with 'asymptotic' contain unspecified homogenous solutions represented by a tensor at each order in 1/r, while files starting with 'asymptoticmatched' have seen these homogeneous solutions determined using the explicit formulas; here the suffixes 'hom' and 'part' separate homogenous terms from the particular solution, the file without suffix is the complete result and the sum of the two.

The directory asymptoticcoeffs/ contains the potentials and their derivatives decomposed order-by-order in the expansion at infinity (the order suffix in the file names). Here, matched expressions were used whenever available.
