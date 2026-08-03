# Notebook Guidelines

Each notebook should read as a short computational study rather than as an unannotated sequence of commands.

## Required structure

1. **Title and purpose.** State the physical or numerical question.
2. **Model.** Define variables, units, governing equations, assumptions, initial conditions, and boundary conditions.
3. **Method.** Identify the algorithm, discretization, solver, tolerances, and important parameters.
4. **Implementation.** Separate imports, reusable functions, parameter definitions, execution, and visualization.
5. **Verification.** Compare against an analytical solution, conservation law, limiting case, convergence test, or independent solver whenever possible.
6. **Interpretation.** Explain what the output establishes and what it does not establish.
7. **References.** Cite the model and numerical method using stable bibliographic links or keys from `references/references.bib`.

## Reproducibility

- Run the notebook from a fresh kernel in top-to-bottom order.
- Set and document random seeds for stochastic calculations.
- Avoid absolute local paths and undocumented external data.
- State physical units explicitly; use dimensionless variables only after defining the scaling.
- Keep generated media traceable to the notebook and parameters that produced it.
- Record versions of dependencies in `requirements.yml` when adding a new library.
- Distinguish numerical observation, empirical validation, and mathematical proof.

## Numerical review

A result intended for research use should address truncation error, round-off error, solver tolerances, convergence, parameter sensitivity, and reproducibility. A visually plausible trajectory is not a validation test.
