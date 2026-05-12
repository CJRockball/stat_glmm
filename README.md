# stat_glmm

A compact collection of Jupyter notebooks illustrating generalized linear mixed models (GLMMs) and related hierarchical modeling workflows using synthetic semiconductor manufacturing examples.[page:1][code_file:2]

## Overview

This repository focuses on worked notebook examples rather than a packaged Python library. The notebooks cover binary outcomes, count outcomes, and continuous-response mixed models with random effects, using semiconductor yield, leakage, and defect-count scenarios as motivating examples.[code_file:2]

## Repository contents

| Notebook | Summary |
|---|---|
| `binomial_yield.ipynb` | Builds a hierarchical binomial/logistic modeling workflow for semiconductor yield, starting from synthetic data, exploratory analysis, and pooled logistic regression, then moving to mixed-effects modeling for pass probability.[code_file:2] |
| `poisson_negbin_count.ipynb` | Studies defect-count data using Poisson and negative-binomial models, including mixed-model structure and overdispersion handling for hierarchical count data.[code_file:2] |
| `random_intercept.ipynb` | Introduces a random-intercept mixed model for leakage current as a function of humidity, with variance decomposition and comparison against a pooled linear baseline.[code_file:2] |
| `random_slope_inter.ipynb` | Extends the mixed-model setup to include both random slopes and random intercepts, emphasizing humidity-specific variability and out-of-sample model comparison.[code_file:2] |

## Themes covered

- Generalized linear mixed models (GLMMs) and hierarchical modeling.[code_file:2]
- Synthetic semiconductor manufacturing datasets for yield, leakage, and defect analysis.[code_file:2]
- Model comparison between pooled and mixed-effects approaches.[code_file:2]
- Binomial, Poisson, and negative-binomial response modeling.[code_file:2]
- Random intercept and random slope formulations.[code_file:2]
- Practical notebook-based analysis with `statsmodels`, `numpy`, `pandas`, `matplotlib`, and related scientific Python tools.[code_file:2]

## Intended use

This repo is best used as a small reference library of worked examples for learning or revisiting core GLMM patterns. It is especially useful for users who want notebook-first demonstrations of hierarchical modeling ideas in an applied setting rather than a production-ready software package.[code_file:2]

## Notes

The repository currently contains four notebooks and an Apache-2.0 license, but no README on the GitHub landing page.[page:1] Adding this summary would make the project easier to understand at a glance.[page:1][code_file:2]
