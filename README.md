Project Structure – README
This repository is organized into two main folders, each serving a different purpose in the SHAP-based predictive maintenance analysis:

notebooks folder
Contains the initial modeling and SHAP analysis for each dataset.

Each notebook runs a single instance of a machine learning model (Random Forest or XGBoost).

SHAP values are computed for that one-time model run, providing a quick, interpretable snapshot of feature importance.

Ideal for exploratory analysis and early insight generation.

Trials folder
Contains the full 25-trial experimental setup for each dataset and model.

Both Random Forest and XGBoost models are trained 25 times with randomized splits to account for performance variability.

SHAP values are averaged across trials to produce more robust and reliable feature importance estimates.

Includes comparison of model accuracy and interpretability consistency.

