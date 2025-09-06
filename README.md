1000 Companies Project - Profit Prediction Analysis
📋 Project Overview
This project analyzes a dataset of 1000 companies to build a predictive model for company profits based on various financial metrics. The analysis uses multiple linear regression to predict profits from R&D spending, Administration costs, Marketing spending, and company location.

🏢 Dataset Information
The dataset contains information about 1000 companies with the following features:

R&D Spend: Research and Development expenditure

Administration: Administrative costs

Marketing Spend: Marketing budget

State: Company location (categorical)

Profit: Target variable to predict

🛠️ Technologies Used
Python 3.12.4

Jupyter Notebook

Key Libraries:

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

📊 Analysis Steps
1. Data Loading and Exploration
Imported necessary libraries

Loaded the dataset from CSV file

Examined the first few rows to understand the data structure

2. Data Preprocessing
Separated features (X) and target variable (y)

Encoded categorical variable "State" using LabelEncoder and OneHotEncoder

Handled dummy variable trap by removing one column

Split data into training and testing sets (80/20 split)

3. Exploratory Data Analysis
Created correlation heatmap to understand relationships between numerical variables

Visualized data distributions and relationships

4. Model Building
Implemented Linear Regression model

Trained the model on the training dataset

Made predictions on the test set

5. Model Evaluation
Calculated R² score to evaluate model performance

Achieved an R² score of 0.935, indicating excellent predictive accuracy

📈 Results
The linear regression model achieved 93.5% accuracy in predicting company profits based on the given features, demonstrating strong predictive power.
