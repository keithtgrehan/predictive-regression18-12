#ReadMe Edit
# Predictive Regression

This repo is about building regression models that **generalize to new data**, not just models that look good on the training set.

The work focuses on understanding **why models break**, how overfitting happens, and how to control it using proper evaluation and regularization.

## What I worked on

### 1. Bias–Variance Tradeoff
- Trained models with increasing complexity.
- Observed underfitting vs overfitting in practice.
- Used train/test splits to evaluate real performance.
- Chose model complexity based on **test error**, not training error.

### 2. Regularization
- Started with linear regression and showed how it overfits with interaction features.
- Applied Ridge and Lasso to constrain model complexity.
- Tuned `alpha` to balance bias and variance.
- Learned when Ridge is better (stability) and when Lasso is better (feature selection).

### 3. Detecting Outliers
- Examined how outliers influence regression results.
- Learned to separate bad data from valid extreme cases.
- Treated outliers as both a technical and business decision.

## Challenges we had to overcome
- Environment and dependency issues with **Python, Pandas, and SciPy**.
- Version conflicts that broke imports and model training.
- Debugging errors caused by incompatible library versions.
- Rebuilding virtual environments and fixing requirements to get everything running cleanly.

These issues were part of the learning process and reinforced the importance of reproducible environments.

## Key takeaways
- Always evaluate models on unseen data.
- Lower training error does not mean better generalization.
- Model simplicity often beats complexity.
- Regularization is essential once feature space grows.
- Clean environments matter as much as clean data.

## Tools used
- Python
- NumPy, Pandas, SciPy
- scikit-learn
- VS Code notebook