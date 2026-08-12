# Computational Physics

Computational physics converts physical models into numerical experiments that can be inspected, reproduced, and challenged. It complements analytical work when nonlinear equations, many-body interactions, stochastic processes, or high-dimensional models preclude closed-form solutions. A credible computation, however, is more than a plot: the governing assumptions, discretization, numerical method, parameters, error sources, and software environment must all remain visible. This repository is an academic collection of lecture notes, executable notebooks, simulations, animations, and exploratory studies. Its present scope includes classical mechanics, nonlinear dynamics, statistical methods, scientific visualization, and scientific machine learning. The repository is deliberately organized as a collection of independent teaching units rather than as a software package or a strictly linear course. The notebooks serve three related purposes: to derive physical models, to implement numerical methods, and to compare computational output with theoretical expectations. Rendered GIF and MP4 files are retained as teaching artifacts, while the notebooks remain the authoritative computational source. Experimental machine-learning material is identified as such; numerical agreement is evidence, not proof.

# Repository map

| Area | Material | Main methods |
|---|---|---|
| Classical mechanics | [Harmonic oscillator](harmonic_oscillator/), [double pendulum](double_pendulum_dynamical_system/), [bouncing balls](bouncing_balls/) | ODE integration, event rules, animation |
| Statistical computation | [Statistical distributions](statistical_distribution/), [logarithmic binning](logarithm_binning/) | Sampling, histograms, cumulative distributions, regression |
| Scientific visualization | [Animated time series](time_series_graph_example/) | Matplotlib animation and data presentation |
| Scientific machine learning | [Physics-informed pendulum](pinn_simple_pendulum/), [generative adversarial networks](generative_adversarial_networks/) | Automatic differentiation, neural optimization, distribution learning |
| Methodological studies | [LLM evaluation](avaliacao_llm/) | Comparative analysis of generated scientific reasoning |

See [CONTENTS.md](CONTENTS.md) for the complete notebook-level catalogue and [REFERENCES.md](REFERENCES.md) for the curated bibliography.

# Reproducible environment

The Conda specification contains the shared dependencies used across the notebooks:

```bash
conda env create -f requirements.yml
conda activate computational-physics
jupyter lab
```

PyTorch notebooks can use a CPU installation. Matplotlib animations exported to MP4 also require `ffmpeg`; GIF exports use Pillow. The Pygame example opens a graphical window and may not run in a headless notebook service without display configuration. Notebooks are heterogeneous historical teaching artifacts. Before relying on a result, restart the kernel and run all cells in order. The expected structure and review criteria are specified in [NOTEBOOK_GUIDELINES.md](NOTEBOOK_GUIDELINES.md).

# Academic use

Material may be added as lecture notes, worked computational problems, numerical experiments, or research prototypes. Each contribution should state the physical model, numerical method, parameter choices, expected result, and relevant references. Reusable figures should identify the notebook that generated them. Proposed changes are described in [CONTRIBUTING.md](CONTRIBUTING.md), and citation metadata are provided in [CITATION.cff](CITATION.cff).

# Limitations

The examples prioritize exposition and experimentation. They have not all been benchmarked for numerical stability, convergence order, performance, or hardware portability. Outputs should therefore be reproduced and independently checked before being used in research or assessment.

# Author

**Dr. Osvaldo L. Santos-Pereira** — [Academic webpage](https://ozsp12.github.io/) · [Lattes](http://lattes.cnpq.br/6730251976463283) · [ORCID](https://orcid.org/0000-0003-2231-517X) · [Google Scholar](https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en) · [ResearchGate](https://www.researchgate.net/profile/Osvaldo-Santos-Pereira) · [GitHub](https://github.com/ozsp12) · [LinkedIn](https://www.linkedin.com/in/ozsp12) · [Substack](https://substack.com/@olsp1982) · [Medium](https://medium.com/@ozsp12) · [YouTube](https://www.youtube.com/@ozlsp12) · [X](https://x.com/ozsp12)

# Repository policy

Existing folder and notebook names remain stable whenever practical so that published links continue to work. No license is asserted by this documentation update; reuse is governed by the repository owner's terms and applicable law.
