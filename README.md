Overview
This project predicts the likelihood of bankruptcy in banks/companies using financial indicators.
The dataset, collected from the Taiwan Economic Journal (1999–2009), contains financial ratios and key performance indicators.
The task is to classify firms as bankrupt or non-bankrupt based on these features.

Features
Preprocessed financial dataset (1999–2009) from Taiwan Economic Journal.
Applied machine learning models: Logistic Regression, Decision Trees, Random Forest, XGBoost.
Evaluated models using accuracy, precision, recall, F1-score, ROC-AUC.
Analyzed feature importance to identify critical financial risk factors.

Tech Stack
Python: pandas, numpy, scikit-learn, xgboost
Visualization: matplotlib, seaborn
Notebook: Jupyter

Results
XGBoost outperformed baseline models with strong predictive accuracy.
Key financial indicators such as liquidity and debt ratios were strong predictors of bankruptcy.
