Old Car Price Prediction: Regression

Project Overview

This project focuses on predicting used car prices using multiple machine learning regression algorithms. A complete end-to-end workflow was implemented including data cleaning, feature engineering, preprocessing, model training, hyperparameter tuning, evaluation, and model comparison.

The goal was to identify the best-performing algorithm for car price prediction based on real-world vehicle features.

⸻

Dataset Description

Input Features (X)
	•	Car Brand / Make
	•	Car Model
	•	Fuel Type
	•	Transmission Type
	•	Engine Capacity
	•	Max Power
	•	Max Torque
	•	Kilometers Driven
	•	Ownership Details
	•	Car Age
	•	Other encoded categorical features

Target Variable (y)
	•	Car Price

⸻

Project Workflow
	1.	Import Libraries
	2.	Load & Inspect Dataset
	3.	Clean Text-Based Numeric Columns
	4.	Handle Missing Values
	5.	Feature Engineering (Car Age)
	6.	Outlier Removal (IQR Method)
	7.	Encode Categorical Variables (One-Hot Encoding)
	8.	Train-Test Split
	9.	Feature Scaling (StandardScaler)
	10.	Train Multiple Regression Models
	11.	Hyperparameter Tuning (GridSearchCV)
	12.	Evaluate & Compare Models

⸻

Model Evaluation Comparison

Model	MAE	RMSE	R² Score
Linear Regression	562114.67	1984284.00	-4.3129
Ridge Regression	199476.20	403082.66	0.7808
Lasso Regression	187216.05	496289.80	0.6677
ElasticNet Regression	174209.16	355345.20	0.8296


⸻

Best Performing Model

ElasticNet Regression achieved the best performance among the compared linear models.

⸻

Key Learnings

Plain Linear Regression fails on complex real-world datasets with high variance
Regularization (Ridge, Lasso, ElasticNet) significantly improves generalization
Feature engineering (e.g., Car Age) and proper preprocessing have a strong impact on model accuracy
Model comparison is essential — no single algorithm wins without evaluation

⸻

Conclusion

This project demonstrates the importance of preprocessing, feature engineering, and comparing multiple algorithms to build a strong regression model for real-world price prediction.
