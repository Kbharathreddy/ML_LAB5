This project analyzes a workplace mental-health survey to investigate factors associated with treatment-seeking behavior. It implements:
 Linear regression using a single feature (`Days_Indoors`).
 Evaluation of regression metrics (MSE, RMSE, MAPE, R²) 
 Linear regression using all preprocessed features.
 K-Means clustering (k = 2) for exploratory segmentation.

Key finding: using all features improved explanatory power (R² ≈ 0.16) compared to the single-feature model, but linear regression still underfits the dataset. Clustering revealed temporal/segment differences that merit further validation.
