# Anisotropy-of-Stiffness-Tetrads

This script calculates the distances of a given stiffness C tetrad to its 
projections C_i=P_i * C onto 7 of the 8 symmetry classes of elasticity (every C is trclinic). The distance is defined as d_i=1-|C_i|/|C|, being 0 if C falls into the symmetry class i and not exceeding 1. As the axes of anisotropy are unknown, d is minimized over three rotation angles. 

Detailes can be found in M.Weber, R.Glüge, and A.Bertram. Distance of a stiffness tetrad to the symmetry classes of linear elasticity. International Journal of Solids and Structures, 156-157:281--293,2019. https://doi.org/10.1016/j.ijsolstr.2018.08.021.

