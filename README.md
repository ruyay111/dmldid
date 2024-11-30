DMLDiD: Double Machine Learning for Difference-in-Differences

OVERVIEW

This repository contains the implementation of the Double Machine Learning (DML) approach for Difference-in-Differences (DiD) analysis. The DMLDiD combines the strengths of traditional Difference-in-Differences for causal inference with modern machine learning techniques to estimate the treatment effect more robustly in the presence of high-dimensional covariates. This method helps address potential biases from confounding variables and non-linearities that can be challenging for conventional econometric models.

MOTIVATION

The primary motivation behind this project is to enhance causal inference capabilities by utilizing machine learning methods, particularly in assessing the impact of policies or interventions. By incorporating DML, this approach strives to provide reliable treatment effect estimates even in complex data environments where traditional linear models may be insufficient or less effective.

FEATURES

Double Machine Learning Framework: Integrates machine learning estimators with a Difference-in-Differences setup to control for confounding variables in high-dimensional data settings.

Cross-Fitting: Employs cross-fitting techniques to minimize overfitting and enhance the robustness of treatment effect estimates.

RESULTS

The results section of the output provides the estimated Average Treatment Effect (ATE), accounting for confounding factors through machine learning-based adjustments.

REFERENCE

Card, D., & Krueger, A. (n.d.). Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania. Retrieved 2024, from https://davidcard.berkeley.edu/papers/njmin-aer.pdf

Chang, N.-C. (2020, May). Double/debiased machine learning for difference-in-differences models. https://academic.oup.com/ectj/article/23/2/177/5722119

Callaway, B., Goodman-Bacon, A., & Sant’Anna, P. H. C. (2024, January 26). Difference-in-Differences with a Continuous Treatment. https://arxiv.org/pdf/2107.02637

