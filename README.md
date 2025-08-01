Project Structure – README
This repository is organized into three main folders and a PDF File, each serving a specific purpose in the SHAP-based predictive maintenance analysis:
results/

Contains a compiled PDF report showing the overall results for both XGBoost and Random Forest.

Summarizes key findings, including:

1-trial vs 25-trial SHAP stability

Cross-dataset feature importance comparisons

Operational and business implications

Serves as a single reference document for stakeholders and poster presentations.

notebooks/
Contains the initial modeling and SHAP analysis for each dataset.

Each notebook runs a single instance of a machine learning model (Random Forest or XGBoost).

SHAP values are computed from that one-time model run, offering a quick, interpretable snapshot of feature importance.

Ideal for exploratory analysis and early-stage insights.

trials/
Contains the full 25-trial experimental setup for each dataset and model.

Both Random Forest and XGBoost models are trained 25 times with randomized splits to address performance variability and data imbalance.

SHAP values are averaged across trials, providing robust and stable feature importance estimates.

trial_v/
Summarizes the results of the 25-trial experiments in a concise, visualization-ready format.

Focuses on SHAP-based feature importance comparisons across datasets and models.

Contains aggregated bar plots and ranking tables.




