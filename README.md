# Diabetes-Prediction-System

### Problem Statement
- Diabetes is a group of diseases characterized by high blood sugar levels due to insufficient insulin production or improper use of insulin by the body. This condition can lead to various health complications, including heart disease, blindness, and kidney failure. Therefore, early detection and management are essential for reducing the risk of complications and improving the quality of life for individuals with diabetes.

### Dataset Description
The dataset used for this project contains the following features:

- Pregnancies: Number of times pregnant
- Glucose: Plasma Glucose Concentration (mg/dl)
- Blood Pressure: Diastolic Blood Pressure (mmHg)
- Skin Thickness: Triceps SkinFold Thickness (mm)
- Insulin: 2-Hour Serum Insulin (mu U/ml)
- BMI: Body Mass Index (weight in kg/ height in m^2)
- Diabetes Pedigree Function: Measure of diabetes history in relatives
- Age: Age of the patient (years)
- Outcome: Class Variable (0 or 1), where 0 indicates no diabetes and 1 indicates diabetes.

### Approach
This project follows a systematic approach to develop and deploy a predictive model for diabetes detection:

= Data Cleaning: Identify and handle missing values, outliers, and inconsistencies in the dataset to ensure data quality.
- Data Preprocessing: Standardize or normalize features, encode categorical variables, and split the data into training and testing sets.
- Exploratory Data Analysis (EDA): Visualize the distribution of features, explore relationships between variables, and gain insights into the dataset.
- Statistical Analysis: Conduct statistical tests to validate assumptions and identify significant predictors of diabetes.
- Feature Engineering: Create new features or transform existing ones to improve the performance of machine learning models.
- Feature Selection: Select the most relevant features using techniques like correlation analysis, feature importance, or dimensionality reduction.
- Machine Learning Models:
-- Random Forest Classifier: Ensemble learning method that combines multiple decision trees to make predictions.
-- K-Nearest Neighbors (KNN): Non-parametric algorithm that classifies data points based on the majority vote of their neighbors.
-- Logistic Regression: Statistical model used for binary classification by estimating the probability of the outcome.
