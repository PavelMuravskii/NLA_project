# NLA_project - Eigenjoy Enthusiasts
The goal of this project is to select the best interpolation method for a coarse grid of novier stokes. And also to analyse the applicability of linear matrices for read-only solutions of this equation

# First steps

First of all, we have selected the boundary conditions for the Novier-Stokes equation. 

Then this equation was solved numerically for two cases of vortex laminar flow and for laminar flow in a pipe. For laminar flow in a pipe, the Novier-Stokes equation was solved analytically.
# Interpolation 

The scaling of the grid from 64 by 64 to 128 by 128 using various interpolation methods was then studied. Such as nearest neighbour method, linear interpolation, cubic and cubic interpolating Hermite polynomial. To compare the obtained results, the metric chosen was the relative error in the second matrix norm, which is the following formula: $\frac{\Vert \hat{A} - A \Vert}{\Vert A \Vert}$. 

# Spare matrices
After that, a study was also conducted to speed up the algorithm using spare matrices as well as the Jacobi method
