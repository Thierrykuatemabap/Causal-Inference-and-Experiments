# Causal Inference Experiments for TU Delft PhD Application

This folder contains a set of simple and reproducible Jupyter notebooks on causal inference and machine learning.

The goal is to demonstrate practical understanding of:

- confounding bias;
- propensity score estimation;
- inverse probability weighting (IPW);
- positivity / overlap violations;
- simulation-based comparison of causal estimators.

## Notebooks

1. `01_simulation_confounding_bias.ipynb`  
   Shows how a confounder can create bias in naive treatment effect estimation.

2. `02_propensity_score_and_ipw.ipynb`  
   Estimates propensity scores using logistic regression and applies IPW to estimate the average treatment effect.

3. `03_positivity_violation.ipynb`  
   Illustrates poor overlap and unstable IPW weights under near-positivity violation.

4. `04_monte_carlo_naive_vs_ipw.ipynb`  
   Runs a Monte Carlo comparison of naive regression, adjusted regression, and IPW.

## How to run

Install the required packages:

```bash
pip install -r requirements.txt
```

Then launch Jupyter:

```bash
jupyter notebook
```

Run the notebooks in order.

## Suggested GitHub repository name

`Causal-Inference-Experiments`

## Suggested GitHub description

Simple and reproducible causal inference experiments illustrating confounding bias, propensity score estimation, positivity violations, and IPW estimation using Python.

## Relevance to the TU Delft PhD project

These notebooks are aligned with a research direction in causal inference and machine learning because they illustrate core assumptions behind causal estimation and show how violations of these assumptions affect statistical learning and decision-making.
