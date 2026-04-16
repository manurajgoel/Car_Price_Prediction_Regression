🚗 Old Car Price Prediction: Regression



📌 Project Overview

This project focuses on predicting used car prices using multiple machine learning regression algorithms. A complete end-to-end workflow was implemented including data cleaning, feature engineering, preprocessing, model training, hyperparameter tuning, evaluation, and model comparison.

The main goal was to identify the best-performing algorithm for car price prediction using real-world vehicle features.

⸻

📂 Dataset Description

🔹 Input Features (X):

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
	•	Other Encoded Categorical Features


🎯 Target Variable (y):

	•	💰 Car Price

⸻

⚙️ Project Workflow:

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

📈 Model Evaluation Comparison

🔹 Linear Regression

	•	MAE : 562114.67
	•	RMSE: 1984284.00
	•	R² Score: -4.3129


🔹 Ridge Regression

	•	MAE : 199476.20
	•	RMSE: 403082.66
	•	R² Score: 0.7808


🔹 Lasso Regression

	•	MAE : 187216.05
	•	RMSE: 496289.80
	•	R² Score: 0.6677


🔹 ElasticNet Regression

	•	MAE : 174209.16
	•	RMSE: 355345.20
	•	R² Score: 0.8296

⸻

🏆 Best Performing Model:

✅ ElasticNet Regression achieved the best performance among the compared linear models.

⸻

📚 Key Learnings:

	•	Plain Linear Regression may fail on complex real-world datasets with high variance
	•	Regularization (Ridge, Lasso, ElasticNet) significantly improves generalization
	•	Feature engineering (Car Age) and proper preprocessing strongly improve model accuracy
	•	Model comparison is essential — no single algorithm wins without evaluation

⸻

🎯 Conclusion

This project demonstrates the importance of preprocessing, feature engineering, and comparing multiple algorithms to build a strong regression model for real-world price predion.
