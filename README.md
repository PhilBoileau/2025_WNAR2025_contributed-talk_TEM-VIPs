# A nonparametric framework for treatment effect modifier discovery in high dimensions

## Authors

Philippe Boileau, Ning Leng, Nima Hejazi, Mark van der Laan, and Sandrine Dudoit

## Abstract

### English:

Heterogeneous treatment effects are driven by treatment effect modifiers (TEMs),
pre-treatment covariates that modify the effect of a treatment on an outcome.
Current approaches for uncovering TEMs are limited to low-dimensional data, data
with weakly correlated covariates, or parametric data-generating processes. We
resolve these issues by developing a framework for defining model-agnostic TEM
variable importance parameters appropriate for high-dimensional data with
arbitrary correlation structure, deriving causal machine learning estimators of
these parameters, and establishing these estimators' asymptotic properties.
Simulation experiments demonstrate that these estimators' asymptotic guarantees
are approximately achieved in realistic sample sizes for observational and
randomized studies alike. This framework is applied to gene expression data
collected during a clinical trial investigating the effect of a novel treatment
on disease-free survival in breast cancer.

## Related Papers

- [A flexible approach for predictive biomarker
  discovery](https://academic.oup.com/biostatistics/advance-article/doi/10.1093/biostatistics/kxac029/6647929)
  by Boileau et al. (2022)
- [A nonparametric framework for treatment effect modifier discovery in high
  dimensions](https://academic.oup.com/jrsssb/article/87/1/157/7738222) by Boileau et al. (2025)

## Related R Packages

- [uniCATE](https://github.com/insightsengineering/uniCATE)
- [unihtee](https://github.com/insightsengineering/unihtee)
