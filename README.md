# Titanic Survival Prediction

Built a logistic regression model to predict survival on the Titanic dataset using Python (pandas, scikit-learn).  
Features: passenger class and age (after dropping missing).  
Validated with 5-fold cross-validation (mean accuracy ≈ 69.9%, std ≈ 6.0%), outperforming a naive “most frequent” baseline by ~10.5 percentage points.

## How to reproduce locally

```bash
source ~/venv/bin/activate
jupyter lab
