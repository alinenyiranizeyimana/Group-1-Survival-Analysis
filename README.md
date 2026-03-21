# Group 1 Survival Analysis Project

## Project Title

**Parametric Survival Analysis of the Veterans’ Administration Lung Cancer Dataset**

## Overview

This project applies survival analysis techniques to study time-to-event data from the Veterans’ Administration lung cancer dataset. The goal is to understand patient survival patterns, compare parametric models, and identify the best model for describing survival behavior.

##  Objectives

* Model survival time using parametric survival models
* Compare models using log-likelihood and Akaike Information Criterion (AIC)
* Select the best-fitting model
* Analyze survival and hazard functions over time
* Interpretation
* Recommandation

## Dataset

The dataset contains clinical information for 137 lung cancer patients, including:

* Survival time
* Event indicator (death or censored)
* Treatment group (standard vs test)
* Age and performance score (Karnofsky)
* Cancer cell type and prior therapy

## Methods

The following methods were applied:

* Kaplan–Meier estimation for non-parametric survival analysis
* Parametric models:

  * Exponential
  * Weibull
  * Log-normal
  * Log-logistic
  * Gompertz
  * Gamma
  * Generalized Gamma

Model comparison was based on AIC and log-likelihood.

## Key Results

* Survival probability declines rapidly at early times, indicating high initial risk
* No strong difference in survival between treatment groups
* The **Generalized Gamma model** provided the best fit (lowest AIC)
* The hazard is not constant and changes over time

## Interpretation

The results show that survival varies widely among patients, with many early deaths and a few long-term survivors. Flexible models like the generalized gamma distribution better capture this pattern compared to simpler models.

## Limitations

* Small sample size
* Limited covariate analysis
* Results depend on chosen model assumptions

## Future Work

* Include covariates using regression models (e.g., Cox model)
* Extend analysis to other medical datasets
* Investigate treatment effects in more detail

## Team Members

* Aline
* Anicet
* Mireille
* Sidoine
* Sandra

##  Tools Used

* R (survival, flexsurv, survminer)
* LaTeX (Beamer)

##  Conclusion

This project demonstrates the importance of flexible parametric models in survival analysis. The generalized gamma model best captures the complex survival patterns observed in lung cancer patients.

---
