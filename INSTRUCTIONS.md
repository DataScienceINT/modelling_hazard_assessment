# Student Instructions

This repository contains the material for a short lesson on modelling and computation in hazard assessment. The main in-class activity is `notebooks/01_lab1_local.ipynb`. The second notebook, `notebooks/02_lab2_extra_local.ipynb`, is an optional extra assignment.

## Before The Lesson

Install `uv`, then prepare the Python environment from the repository root:

```bash
uv sync
uv run jupyter lab
```

Open `notebooks/01_lab1_local.ipynb` in JupyterLab.

## During Lab 1

Work through the early parts of Lab 1 yourself:

- environment check and dataset loading
- exploratory data analysis
- filtering ambiguous labels
- molecular visualisation
- conversion from SMILES to RDKit molecules
- Morgan fingerprint calculation

The following parts are instructor-led demos:

- the structural similarity versus biological activity section, because the pairwise similarity calculation is slower and the main learning goal is interpretation
- the feed-forward neural network section, especially model architecture, training, train/test split, and class imbalance handling

You should still run the demo cells if time allows, but focus on understanding what each step changes in the modelling workflow.

## After The Lesson

Use `notebooks/02_lab2_extra_local.ipynb` as extra practice. It extends Lab 1 with cross-validation, learning curves, and model-selection concepts. Some cells train several models and may take longer to run than the Lab 1 exercises.
