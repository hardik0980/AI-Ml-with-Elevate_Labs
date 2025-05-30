# Titanic Data Preprocessing Pipeline

> A complete, reusable workflow for:
> - importing & exploring data  
> - handling missing values  
> - encoding categorical variables  
> - scaling numeric features  
> - visualizing & removing outliers
>
>Task - 2
>
> 1.Generate summary statistics (mean, median, std, etc.).
2.Create histograms and boxplots for numeric features.
3.Use pairplot/correlation matrix for feature relationships.
4.Identify patterns, trends, or anomalies in the data.
5.Make basic feature-level inferences from visuals.



Sure! Here's a **GitHub-friendly EDA summary** (in Markdown format) for your Titanic dataset analysis. You can directly copy-paste this into your GitHub README.md file:


**TASK - 2**

Exploratory Data Analysis (EDA) Summary - Titanic Dataset

1. Summary Statistics

Calculated **mean**, **median**, **standard deviation**, etc., for all numerical features.
  Age mean: \~29 years, with some missing values.
  Fare had a wide range, with a few passengers paying extremely high amounts.
  Survived distribution was imbalanced (more passengers did not survive).


2. Histograms & Boxplots

Histograms revealed:

  Age was normally distributed.
    Fare was right-skewed (many low values, few high ones).
  Boxplots showed:

  Outliers in Fare and Age.
  Class-based differences in fare prices.

 Patterns, Trends & Anomalies

Patterns

* Higher **fare** → higher chance of **survival**.
* Lower **class** → lower chance of **survival**.
* Most passengers were from **3rd class**.
* Majority aged between **20–40** years.

Trends

Survival was imbalanced: More passengers did not survive.
Women and first-class passengers had better survival rates.

 Anomalies (Outliers)

Fare: A few extreme high values.
Age: Some passengers were unusually old.
SibSp/Parch: A few had unusually large families onboard.


**Task 3 - HOUSE PRICE PREDICTION:**

A machine learning project for housing price prediction using multiple regression models. Includes data cleaning, feature selection, model tuning, and performance comparison using metrics like MSE, MAS and R².

1. Import and preprocess the dataset.
2. Split data into train-test sets.
3. Fit a Linear Regression model using sklearn.linear_model.
4. Evaluate model using MAE, MSE, R².
5. Plot regression line and interpret coefficients.
   

**Task- 4 :Breast Cancer Prediction using Machine Learning**

This project focuses on building a machine learning model to classify breast cancer as malignant or benign using the Breast Cancer Wisconsin (Diagnostic) Dataset.

Key Steps:
Data Loading & Cleaning: Loaded dataset and handled missing/null values.

Exploratory Data Analysis (EDA): Performed basic analysis to understand data distribution.

Feature Selection: Chose important features for better model performance.

Model Building: Trained machine learning models such as Logistic Regression.

Model Evaluation: Achieved a 95% accuracy, using confusion matrix, ROC-Curve and classification report for validation.
