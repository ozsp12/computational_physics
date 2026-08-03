# Double-Pendulum Dynamical System

The double pendulum is a standard nonlinear mechanical system in which deterministic equations can produce strongly divergent trajectories under small perturbations of initial data. The notebook derives the equations from the Euler–Lagrange formalism, integrates the coupled system numerically, and animates the resulting motion.

## Material

- `double_pendulum_dynamical_system.ipynb` — model, equations, numerical pipeline, and visualization.
- `double_pendulum_chaos.gif` and `double_pendulum_chaos.mp4` — rendered trajectory animations.

The simulation illustrates sensitivity to initial conditions; it does not by itself estimate Lyapunov exponents or prove chaotic dynamics. Research use would require solver-tolerance tests, convergence analysis, energy-drift inspection, and comparison with a structure-preserving integrator.

[Return to the repository contents](../CONTENTS.md).
