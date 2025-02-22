# Bayesian-Optimization-of-the-World-Ocean-Model-of-Biogeochemistry-and-Trophic-dynamics-(WOMBAT)
Bayesian optimization of WOMBAT model parameters using surrogate Gaussian Process Regression model

Implementing Gaussian process regression-based Bayesian optimization (G-BO) using the emcee package (https://emcee.readthedocs.io/en/stable/).

For more information about the implementation of G-BO, please refer to the paper - [Gaussian process regression-based Bayesian optimization (G-BO) of model parameters - a WRF model case study of southeast Australia heat extremes](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2024GL111074).

QMC_sample_generator.ipynb script contains the generation of QMC sample over parameter space

WOMBAT_lite.ipynb script contains the implementation of surrogate GPR model training and evaluation, and then Sobol's global sensitivity analysis, and then Bayesian optimization of model parameters.

  More information about the WOMBAT model can be found here - [WOMBAT](https://access-hive.org.au/models/model_components/bgc_ocean/).
