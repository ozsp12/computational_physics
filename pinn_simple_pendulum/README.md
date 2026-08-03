# Physics-Informed Simple Pendulum

This module uses physics-informed neural networks (PINNs) to approximate solutions of Newtonian initial-value problems. The governing differential equation and initial conditions enter the loss function through automatic differentiation. The notebook includes nonlinear pendulum and damped mass–spring examples and supports comparison with conventional numerical solutions.

## Material

- `mvp_simple_pendulum.ipynb` — model definitions, neural architecture, residual construction, training, and deterministic comparison.

PINNs are optimization-based approximators rather than exact solvers. Reported results depend on collocation points, network architecture, scaling, initialization, optimizer, and stopping criterion. Validation against a trusted ODE solver and residual evaluation outside the training points are essential.

The foundational and review literature is listed under [scientific machine learning](../REFERENCES.md#scientific-machine-learning).

[Return to the repository contents](../CONTENTS.md).
