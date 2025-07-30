Project Structure – README
This repository is organized into three main folders, each serving a specific purpose in the SHAP-based predictive maintenance analysis:

notebooks/
Contains the initial modeling and SHAP analysis for each dataset.

Each notebook runs a single instance of a machine learning model (Random Forest or XGBoost).

SHAP values are computed from that one-time model run, offering a quick, interpretable snapshot of feature importance.

Ideal for exploratory analysis and early-stage insights.

trials/
Contains the full 25-trial experimental setup for each dataset and model.

Both Random Forest and XGBoost models are trained 25 times with randomized splits to address performance variability and data imbalance.

SHAP values are averaged across trials, providing robust and stable feature importance estimates.

Includes comparative metrics on model accuracy and interpretability consistency.

trial_v/
Summarizes the results of the 25-trial experiments in a concise, visualization-ready format.

Focuses on SHAP-based feature importance comparisons across datasets and models.

Contains aggregated bar plots, ranking tables, and side-by-side visuals that support presentation and reporting needs.

Designed for communicating insights effectively in research posters or stakeholder reports.



