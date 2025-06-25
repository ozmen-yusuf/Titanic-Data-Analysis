# Data Analysis and Survival Prediction on the Titanic Dataset

## Project Overview

This project presents a comprehensive exploratory data analysis (EDA) and survival prediction for the passengers of the RMS Titanic. The primary goal is to explore the dataset to uncover factors that influenced a passenger's likelihood of survival and to build a basic predictive model. This is a classic project for practicing fundamental data science skills, including data cleaning, feature engineering, data visualization, and machine learning modeling.

## Analysis and Process

The project followed these key steps:

1.  **Data Loading and Initial Exploration:** Loaded the dataset using Pandas and performed an initial inspection to understand its structure, features, and data types.
2.  **Exploratory Data Analysis (EDA):**
    * Analyzed the relationships between various features (like `Pclass`, `Sex`, `Age`, `SibSp`, `Parch`) and the `Survived` target variable.
    * Used libraries like Matplotlib and Seaborn to create visualizations (e.g., bar charts, histograms, heatmaps) to better understand data distributions and correlations.
3.  **Data Cleaning and Preprocessing:**
    * Handled missing values in columns like `Age` using appropriate imputation techniques.
    * Converted categorical features (like `Sex` and `Embarked`) into numerical formats suitable for machine learning models.
4.  **Modeling and Prediction:**
    * Split the data into training and testing sets using `train_test_split`.
    * Trained a machine learning model (e.g., `DecisionTreeClassifier` or `LogisticRegression`) to predict survival outcomes.
    * Evaluated the model's performance using metrics like accuracy score.

## Key Findings

* **Gender:** Female passengers had a significantly higher survival rate than male passengers.
* **Passenger Class (Pclass):** Passengers in the first class had a much higher chance of survival compared to those in the second and third classes.
* **Age:** Children had a higher survival rate than adults.

## Technologies Used

* **Language:** Python 3
* **Libraries:**
    * Pandas for data manipulation and analysis.
    * NumPy for numerical operations.
    * Matplotlib & Seaborn for data visualization.
    * Scikit-learn for machine learning modeling.
