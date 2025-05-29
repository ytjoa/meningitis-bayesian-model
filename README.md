# Bayesian Analysis and Prediction of Acute Bacterial Meningitis

This project investigates diagnostic predictors for acute bacterial meningitis using Bayesian logistic regression. It was completed as a team project, with a focus on probabilistic modeling and variable selection.

## 🧠 My Contributions
- Conducted the literature review and clinical background summary
- Cleaned and pre-processed the patient dataset (`data/`)
- Implemented Hamiltonian Monte Carlo sampling using the NUTS algorithm in R
- Evaluated model performance using BIC and Posterior Inclusion Probability (PIP)

## 🛠️ Tools & Methods
- R, RMarkdown
- Bayesian Logistic Regression
- Hamiltonian Monte Carlo (NUTS via `rstan`)
- Model comparison via BIC, variable selection via PIP

## 📊 Results
- Accuracy: 97%, F1 Score: 96%, AUC: 95%
- Bayesian Logistic Regression with HMC Sampling outperformed Frequentist Logistic Regression
