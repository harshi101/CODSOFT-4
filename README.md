# CODSOFT-4
Sales Prediction Using Python- CODSOFT Internship

This project is a part of the Codsoft Data Science Internship (Task 4)

Objective:

To build a Machine Learning model that can predict Sales based on advertising budget across different channels like TV, Radio, and Newspaper.

Technologies Used:
 - Python
 - Pandas, NumPy (Data Handling)
 - Matplotlib, Seaborn (Data Visualization)
 - Scikit-learn (Model Building & Evaluation)

Steps Followed:

Step 1: Data Loading and Exploration
  - Loaded the dataset using pandas.
  - Displayed the first few records and basic summary statistics.
  - Plotted pairplot and heatmap to explore relationships and check correlation.

Step 2: Preprocessing
  - Selected features: TV, Radio, Newspaper.
  - Set Sales as the target variable.
  - Split the dataset into training and testing sets (80/20 split).

Step 3: Model Training
  - Used LinearRegression from sklearn.linear_model.
  - Trained the model using training data.

Step 4: Model Evaluation
  - Made predictions on test data.
  - Evaluated model performance using MAE, MSE, RMSE, and R² score.

Step 5: Visualization
  - Created a scatter plot to compare actual vs predicted sales.

Model Evaluation:

 - MAE :        	1.27
 - MSE :        	2.91
 - RMSE :         1.70
 - R² Score :   	0.906
   
The model explains approximately 90.6% of the variance in sales.

Visualization:
  - Scatter plot of Actual vs Predicted Sales
  - A red line (perfect prediction line) used for reference

Conclusion:
  - TV advertising is the strongest predictor of Sales.
  - The linear regression model gives high accuracy and can help in making data-driven marketing decisions.

 Dataset:
 - Source: [Kaggle Dataset Link](https://www.kaggle.com/code/ashydv/sales-prediction-simple-linear-regression/input)

Author:

T Harshitha

Codsoft Data Science Intern

#codsoft #datascience #internship
   

