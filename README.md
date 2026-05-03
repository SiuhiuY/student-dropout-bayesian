# Predicting Student Dropout – Group Project

## Overview
This project was completed as part of the **Bayesian Multilevel Models** course. The goal was to develop a comprehensive understanding of Bayesian data analysis within data science using the **brms** R package.

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
- **Update**: After seeing the data, we update our prior beliefs about the parameters to form the **posterior distribution**.
- **Predict**: We then use the **posterior distribution** to derive the **posterior predictive distribution**, which predicts future observations

### Advantages
- Provides **associated uncertainty** through full posterior and predictive distributions
- Allows incorporation of **domain knowledge via priors**, helping constrain predictions to realistic ranges
- Naturally handles **hierarchical data structures**, which is central to multilevel modeling
- Performs well **data-scarce settings**, as it is not heavily dependent on large datasets

### Disadvantages
- Can be **computationally expensive**, especially for large datasets or complex models

