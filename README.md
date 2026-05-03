# Predicting Student Dropout – Group Project

## Overview
This project was completed as part of the **Bayesian Multilevel Models** course. The goal was to develop a practical understanding of Bayesian data analysis by applying multilevel modeling using the **brms** R package.

## Objectives
- Select and explore a dataset with a meaningful grouping structure
- Formulate a clear and relevant research question
- Fit and evaluate multiple suitable models
- Perform:
  - Prior sensitivity analysis
  - Posterior predictive checks
  - Model comparison
- Interpret key parameters in the context of the research question

My contribution included dataset selection, feature selection using **Projpred**, implementation of Model #4, and interpretation of its parameters, as it was the best-performing model. 

## Bayesian Analysis Explained
Instead of a single point estimate, Bayesian analysis represents predictions as **probability distributions** and summarises them using **predictive intervals**, which communicate a range of possible outcomes. 

This uncertainty arises from both the parameters and the data:

- **Parameter uncertainty (Prior)**: Our prior beliefs about the model parameters before observing the data
- **Data variability (Likelihood)**: The inherent noise in the observed data

### Modeling Logic
- **Update**: After observing the data, prior beliefs are updated to form the **posterior distribution**.
- **Predict**: The **posterior distribution** is then used to derive the **posterior predictive distribution**, which represents possible future observations



