# Monte Carlo Simulation of the Ising Model

## Project Description
The Ising model is a mathematical model used in statistical mechanics to study phase transitions. This project involves a Monte Carlo simulation using the Metropolis algorithm for the Ising model without an external magnetic field on a two-dimensional L × L square lattice.

## Calculations
To perform the simulations and generate the plots, the following formulas were used:

1. **Average Spin Value**:

$$ m = \cfrac{1}{L ^2} \sum ^{L^2} _{i,j = 1} S _{ij} $$

2. **Magnetization**:

$$ \langle m \rangle = \cfrac{1}{L^2} \sum^{l_sym}_{m_j} |m_j| $$

3. **Susceptibility**:
   
$$ \mathcal{X} = \cfrac{N}{k_BT} (\langle m^2 \rangle - \langle m \rangle ^2)$$

## Tools Used
- **Python**: For implementing the simulation.
- **Libraries**: numpy, scipy, matplotlib.pyplot, matplotlib.animation, numba, IPython.display

All results and analyses are presented in Polish.


