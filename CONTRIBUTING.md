# Contributing

Contributions should preserve the repository as an auditable academic archive.

## Adding a module

1. Create a descriptive, lowercase folder using underscores.
2. Add a `README.md` defining the physical problem, included files, principal method, and limitations.
3. Structure notebooks according to [NOTEBOOK_GUIDELINES.md](NOTEBOOK_GUIDELINES.md).
4. Add the module to [CONTENTS.md](CONTENTS.md).
5. Add new dependencies to `requirements.yml` and formal sources to `REFERENCES.md` or `references/references.bib`.
6. Restart the kernel, run all cells, and inspect every generated figure before committing.

Do not commit cache directories, virtual environments, temporary exports, credentials, or local machine paths. Large media should be included only when it has clear teaching value and cannot be reproduced conveniently from the notebook.

## Academic standard

Equations and claims require references where appropriate. Numerical results should include a verification strategy and sufficient parameters for replication. Machine-learning output must not be presented as a physical law merely because it fits the training data.
