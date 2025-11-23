# Perturbative Learning Physics-Informed Neural Networks
In this repository, we introduce Perturbative Learning PINNs (PL-PINNs), a novel training strategy designed to stabilize PINN optimization by anchoring the network to a base solution, thus 
allowing the network to remain within the basin of attraction of the global minimum. As a result of this approach, local minima are mitigated, accuracy and convergence are improved, and 
the approach is demonstrated on nonlinear eigenvalue problems, such as the Gross-Pitaevskii equation. The algorithm was built and designed by Matthew Kehoe (mskehoe001@gmail.com)
and Byeong-Ho Bahn (bahn@asu.edu).

## Installation
Run `pip install -r requirements.txt` at the terminal. Some of the main files are

1. `box_pinn_simulation.py`: Calculates and plots the solution of the box eigenfunction using the PL_PINN technique for different modes and eigenvalues.
2. `harmonic_pinn_simulation.py`: Calculates and plots the solution of the harmonic eigenfunction using the PL_PINN technique for different modes and eigenvalues.
3. `gravity_well_pinn_simulation.py`: Calculates and plots the solution of the box eigenfunction using the PL_PINN technique for different modes and eigenvalues.
4. `vary_potential_box_to_harmonic.py`: Calculates and plots the solution as the box eigenfunction transitions to the harmonic eigenfunction.
5. `box_pinn_at_ground_state.py`: Examines the error and loss of the the box eigenfunction at the ground state.
6. `harmonic_pinn_at_ground_state.py`: Examines the error and loss of the the harmonic eigenfunction at the ground state.
7. `gravity_well_pinn_at_ground_state.py`: Examines the error and loss of the the gravity well eigenfunction at the ground state.

## Plotting 

Example 1: Wavefunction of the Box potential at different modes and interaction strengths.

![box_potential](https://axion004.wordpress.com/wp-content/uploads/2025/11/box_potential_simulations.png)

Example 2: Wavefunction of the Harmonic potential at different modes and interaction strengths.

![harmonic_potential](https://axion004.wordpress.com/wp-content/uploads/2025/11/harmonic_potential_simulations.png)

Example 3: Wavefunction of the Gravity Well potential at different modes and interaction strengths.

![gravity_well_potential](https://axion004.wordpress.com/wp-content/uploads/2025/11/gravity_well_potential_simulations.png)

Example 4: Eigenvalues versus interaction strength for various potentials.

![eigenvalue_vs_interaction_strength](https://axion004.wordpress.com/wp-content/uploads/2025/11/eigenvalue_vs_interaction_strength.png)

More examples (with instructions on how to run the code) will be written in a Jupyter notebook.

## Future Development

1. Extensions of the PL-PINN technique to nonlinear problems in 2D and 3D.
2. Further analysis of the Riesz loss at the ground state.
3. More simulations and testing against different classes of nonlinear PDEs.

## References
 
TBD


## Notes

All code within this repository is freely available for use under the terms of the MIT license. However, if you intend to utilize or are currently using the code, especially for academic or research purposes, we kindly request that you send an email to Matthew Kehoe (mskehoe001@gmail.com) or Byeong-Ho Bahn (bahn@asu.edu) with your name, institution, and a brief description of your interest in this work. If you use the PL-PINN algorithm in any work resulting in a scientific or academic publication, we would greatly appreciate it if you could cite the PL-PINN algorithm in your manuscript as follows:

TBD
