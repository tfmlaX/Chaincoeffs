# Chaincoeffs
[![license](https://img.shields.io/badge/License-GPL_3.0-orange.svg)](https://github.com/tfmlaX/Chaincoeffs/blob/master/LICENSE) [![Integrated](https://img.shields.io/badge/Integrated_in-MPSDynamics.jl-purple.svg)](https://github.com/angusdunnett/MPSDynamics/)

Julia code to generate finite temperature chain coefficients (on-site energy, hopping energy and coupling constant) of a chain-mapped bosonic environment [1,2].

Part of this code is a translation in Julia from a previous Matlab code [3,4].

These routines have been integrated in the [MPSDynamics.jl](https://github.com/angusdunnett/MPSDynamics/) package.

# Publications
Chaincoeffs is cited in the following publications:
- A. Riva, D. Tamascelli, A. J. Dunnett, A. W. Chin, *Thermal cycle and polaron formation in structured bosonic environments*, [Phys. Rev. B 108(19):195138](https://doi.org/10.1103/PhysRevB.108.195138), November 2023

# References
[1] Chin, A.W. et al. (2010) ‘Exact mapping between system-reservoir quantum models and semi-infinite discrete chains using orthogonal polynomials’, Journal of Mathematical Physics, 51(9), p. 092109. doi:https://doi.org/10.1063/1.3490188.

[2] Tamascelli, D. et al. (2019) ‘Efficient Simulation of Finite-Temperature Open Quantum Systems’, Physical Review Letters, 123(9), p. 090402. doi:https://doi.org/10.1103/PhysRevLett.123.090402.

[3] Gautschi, W. (1994) ‘Algorithm 726: ORTHPOL–a package of routines for generating orthogonal polynomials and Gauss-type quadrature rules’, ACM Transactions on Mathematical Software, 20(1), pp. 21–62. doi:https://doi.org/10.1145/174603.174605.

[4] Gautschi, W. (2005) ‘Orthogonal polynomials (in Matlab)’, Journal of Computational and Applied Mathematics, 178(1–2), pp. 215–234.
