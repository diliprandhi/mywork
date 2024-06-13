# Smart Insurance Pricing

## Description:
This project involves developing a model to predict insurance prices using advanced regression techniques. The goal is to create a smart pricing model that accurately estimates insurance expenses based on various customer attributes.

### Technologies Used:

- **Python Libraries:** NumPy, Pandas, Seaborn, Matplotlib
- **Machine Learning Techniques:** Simple Linear Regression (SLR), Multiple Linear Regression (MLR), Polynomial Regression, Lasso Regression, Ridge Regression, ElasticNet Regression

### Project Breakdown:

**Business Problem Understanding:**
- Define the objective of the analysis, which is to predict insurance expenses based on available features such as age, sex, BMI, number of children, smoking status, and region.

**Data Understanding:**
- Collect and explore the insurance dataset containing 1,338 records with features like age, sex, BMI, children, smoker, region, and expenses.
- Perform initial data exploration to understand the data structure and summary statistics.

**Data Preprocessing:**

- Conduct exploratory data analysis (EDA) to clean the data and handle any missing or inconsistent values.
- Convert categorical variables (sex, smoker, region) into numerical values using encoding techniques.
- Normalize or standardize the data to prepare it for modeling.

**Modeling:**
- Apply Simple Linear Regression to model the relationship between a single feature and insurance expenses.
- Use Multiple Linear Regression to include multiple features in the model, analyzing their combined effect on insurance expenses.
- Implement Polynomial Regression to capture non-linear relationships between features and expenses.
- Employ Lasso Regression for feature selection and regularization to prevent overfitting.
- Use Ridge Regression to address multicollinearity by penalizing large coefficients.
- Apply ElasticNet Regression, combining both Lasso and Ridge regression penalties.

**Evaluation:**
- Assess the performance of each model using metrics such as R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
- Compare the results of different models to identify the best-performing one for predicting insurance expenses.

### Usage:
Clone the repository, install the necessary libraries, and execute the script to input customer attributes and receive a expenses of the the customer so that we can give smart insurance pricing according to theie expenses.
