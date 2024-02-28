# Advective Flow Study

## Overview
This repository contains code and results from a study comparing analytical and numerical methods for analyzing advective flow phenomena. Advective flow is a crucial aspect of various natural and industrial processes, including groundwater flow and chemical engineering applications.

## Files
- `README.md`: This file providing an overview of the repository and its contents.

## Results
![From the comparison graph we can tell that the Numeric solution sketch is rising  while the analytical solution is constant at zero.](images/Pasted%20image.png) Analytical solution is continuous in nature and numeric solution is discrete in nature, we can explain this from the results. Analytical solution provides a continuous prediction of the saturation of Phase 1 (S1) as a function of spatial position (x). It starts from zero and gradually increases as x and time (t) progress. On the other hand, the numerical solution yields discrete values of S1, resulting in a step-like curve.
# Capillary Calculation
![Capillary Curve](images/Pasted%20image%201.png)
The capillary pressure constantly rises in change of Sv.
The capillary pressure for all the cases shows a similar output. All tend to rise in change in Sv.

## Usage
To use the provided scripts:
1. Clone this repository to your local machine.
2. Navigate to the directory containing the scripts.
3. Run `analytical_solution.py` and `numerical_solution.py` to obtain the results.
4. Refer to the graphs in the `results/` directory for visual comparisons.

## Dependencies
- Python 
- Matplotlib
- NumPy

## References
- Bear, J., & Cheng, A. H.-D. (2010). Modeling Groundwater Flow and Contaminant Transport (Springer Hydrogeology). Springer.
- LeVeque, R. J. (2007). Finite Difference Methods for Ordinary and Partial Differential Equations: Steady-State and Time-Dependent Problems. Society for Industrial and Applied Mathematics.
- Patankar, S. V. (1980). Numerical Heat Transfer and Fluid Flow. CRC Press.
- Smith, M. W., & Williams, M. B. (2015). Introduction to Chemical Engineering Thermodynamics. McGraw-Hill Education.
- Versteeg, H. K., & Malalasekera, W. (2007). An Introduction to Computational Fluid Dynamics: The Finite Volume Method (2nd ed.). Pearson Education.


