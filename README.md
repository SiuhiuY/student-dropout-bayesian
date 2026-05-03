# Bayesian Multilevel Model – Group Project

## Overview
This project was completed as part of the **Bayesian Multilevel Models** course. The goal was to develop a practical understanding of Bayesian data analysis by applying multilevel modeling using of the **brms** R package.

## Objectives
- Select and explore a dataset with a meaningful grouping structure
- Formulate a clear and relevant research question
- Fit and evaluate multiple multilevel Bayesian models
- Perform:
  - Prior sensitivity analysis
  - Posterior predictive checks
  - Model comparison
- Interpret key parameters in the context of the research question

My contribution include dataset selection, feature selection using using **Projpred**, implementation of Model #4 and interpretation of its parameters as it is the best-performing model. 

## Bayesian analysis explained
Instead of a single point estimate for prediction, Bayesian analysis generates **predictive intervals** that communicates a range of possible outcomes. This uncertainty comes from both the parameters and the data.
- Parameter uncertainty (**Prior**): Our prior knowledge of the model's true parameters.
- Data variability (**Likelihood**): The inherent noise within the observed data itself.

### Modeling logic
- Update: After seeing the real data, we update our belief in the parameters to create the **Posterior distribution**.
- Predict: Using that posterior distribution, we derive **Posterior Predictive distribution** to simulate future observations.



