Diabetes Risk & Actuarial Modeling
Predictive Health Risk Assessment using Ensemble Learning

🩺 Project Context
This project develops a robust statistical framework to estimate the probability of diabetes diagnosis within a clinical population. Beyond simple classification, this work focuses on risk stratification—quantifying individual health risks to support actuarial modeling in health insurance pricing and population health management.

🛠️ Technical Stack
Language: Python

Data Manipulation: pandas, NumPy

Modeling & Evaluation: scikit-learn, XGBoost, CatBoost

🔬 Methodology & Workflow
The analysis follows a rigorous actuarial workflow to ensure both predictive power and model transparency:

Clinical Feature Engineering: Derived metabolic health markers including AIP (Atherogenic Index of Plasma), lipid ratios, and blood pressure intensity to capture non-linear health signals.

Ensemble Architecture: Implemented a Stacked Generalization model using Gradient Boosting machines (XGBoost, CatBoost, HistGBM) to minimize variance and handle high-cardinality demographic features.

Advanced Encoding: Utilized Ordinal and Frequency encoding for demographic variables to maintain feature integrity while optimizing for tree-based splits.

📊 Model Evaluation & Credibility
To meet industry standards for risk assessment, models were evaluated on three dimensions:

Discriminative Ability (ROC-AUC): Measuring the model's capacity to correctly rank high-risk individuals.

Segmentation Accuracy: Utilization of Confusion Matrices to understand Type I and Type II error costs—critical for determining the financial impact of false negatives in health screenings.

Reliability (Calibration Analysis): Ensuring that predicted probabilities correspond to observed frequencies, a requirement for actuarial credibility and insurance premium loading.

🎯 Actuarial Relevance
This repository demonstrates technical proficiency in skills directly applicable to insurance and healthcare analytics:

Applied Risk Modeling: Transforming raw clinical data into actionable risk scores.

Classification under Uncertainty: Balancing predictive precision with the inherent noise of real-world health data.

Predictive Assessment: Building models designed for integration into broader financial and health underwriting systems.
