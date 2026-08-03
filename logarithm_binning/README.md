# Logarithmic Binning

Logarithmic binning is useful when positive observations span several orders of magnitude. Equal widths on a logarithmic scale can reveal structure that is hidden by linear bins, but raw bin counts are not directly comparable when the bin widths differ. Density estimates must therefore include the appropriate width normalization.

## Material

- `logarithmic_binning.ipynb` — compact analysis pipeline using synthetic distributions, cumulative counts, and regression.
- `logarithmic_binning_step_by_step.ipynb` — detailed construction and interpretation of logarithmically spaced bins.

Straight lines on log–log axes are not sufficient evidence for a power law. Parameter estimation and model comparison should use likelihood-based methods and goodness-of-fit tests; see Clauset, Shalizi, and Newman (2009) in [REFERENCES.md](../REFERENCES.md#probability-statistical-computation-and-scaling).

[Return to the repository contents](../CONTENTS.md).
