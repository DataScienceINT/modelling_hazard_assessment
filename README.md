## Modelling Hazard Assessment

This repository contains slide decks, literature, datasets, and Jupyter notebooks for a short teaching event on modelling and computation in hazard assessment.

Student-facing lesson guidance is in [INSTRUCTIONS.md](INSTRUCTIONS.md). Notebook-specific notes are in [notebooks/README](notebooks/README).

## Environment

This project now uses `uv` as the primary environment and dependency manager.

1. Install `uv`.
2. Create and sync the environment:

```bash
uv sync
```

3. Start JupyterLab:

```bash
uv run jupyter lab
```

4. Open the notebooks from JupyterLab.

## Notes

- `pyproject.toml` is the source of truth for dependencies.
- `uv.lock` pins the resolved environment.
- The notebooks are local-first and load data from `datasets/`.
