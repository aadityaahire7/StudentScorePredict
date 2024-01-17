# StudentScorePredict
Supervised Machine Learning

# XGBoost Regression Analysis

This repository contains a Python script for a simple regression analysis using the XGBoost algorithm. The analysis predicts scores based on the number of hours studied, using a dataset retrieved from a remote link.



# Follow the steps below to reproduce the analysis and visualize the results #

# Prerequisites : Make sure you have the required libraries installed #


1. Clone the repository:



2. Run the Jupyter notebook or Python script:



3. Explore the visualizations and results generated.

# Analysis Overview #

1. Data Retrieval:
   - The script retrieves data from the [remote dataset](http://bit.ly/w-data) using the Pandas library.

2. Data Preparation:
   - The dataset is split into features (X) and target variable (y).
   - The data is further divided into training and testing sets.

3. Exploratory Data Visualization:
   - Scatter plots visualize the relationship between hours studied and scores for both training and testing data.
   - A regression line is plotted to illustrate the trend in the training data.

4. XGBoost Regression Model:
   - An XGBoost regressor is created and trained using the training data.

5. Model Evaluation:
   - The model predicts scores based on a hypothetical number of hours (e.g., 9.25 hours).
   - Mean Absolute Error (MAE) is calculated to evaluate the model's performance on the test data.

6. Results Display:
   - The predicted score for the specified number of hours is displayed, along with the MAE.

7. Test Data Visualization:
   - Scatter plots compare the actual test data with the predicted scores.

# Results #

The analysis provides insights into the relationship between hours studied and scores, offering a predictive model for future score estimations.

