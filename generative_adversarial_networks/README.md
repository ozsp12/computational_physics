# Generative Adversarial Networks

This module studies adversarial learning through small distribution-approximation examples. The generator maps random inputs to synthetic samples, while the discriminator attempts to separate synthetic and reference data. Their coupled optimization is visualized during training.

The directory contains a multivariate toy model, a reduced normal-distribution example, rendered training animations, and a presentation. These examples are pedagogical demonstrations: GAN training can be unstable, and visual agreement does not establish distributional equivalence.

## Files

- `generative_adversarial_networks_toy_model.ipynb` — multivariate example.
- `generative_adversarial_networks_simple_version.ipynb` — reduced normal-distribution example.
- `gan_training_progress*.gif` and `gan_training_progress*.mp4` — rendered outputs.
- `gan_presentation.pptx` — supporting presentation.

The foundational reference is Goodfellow et al. (2014), listed in [REFERENCES.md](../REFERENCES.md#scientific-machine-learning).

[Return to the repository contents](../CONTENTS.md).
