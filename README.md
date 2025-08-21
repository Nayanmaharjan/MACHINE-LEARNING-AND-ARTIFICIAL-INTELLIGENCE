# MACHINE-LEARNING-AND-ARTIFICIAL-INTELLIGENCE
An end-to-end data science project demonstrating predictive modeling techniques to forecast international flight numbers using multiple regression algorithms.

# Flight Number Prediction using Regression Models

## 1. Project Overview
This project focuses on building and evaluating machine learning models to predict the total number of flights (`All_Flights`) based on various factors from a comprehensive dataset. The goal is to demonstrate a comprehensive data science workflow, encompassing data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modelling using multiple regression algorithms.

## 2. Dataset
The analysis is performed on a dataset containing detailed flight information. The key columns include:
* **`Month`**: The month and year of the flight.
* **`Australian_City`**: The Australian departure or arrival city.
* **`International_City`**: The international departure or arrival city.
* **`Airline`**: The airline operating the flight.
* **`Route`**: The flight route.
* **`All_Flights`**: The total number of flights (the target variable to be predicted).
* **`Max_Seats`**: The maximum number of seats available.

## 3. Methodology
The following steps were taken to build the predictive models:

* **Data Cleaning and Pre-processing**: Handled categorical and numerical data.
* **Exploratory Data Analysis (EDA)**: Analysed key features, distributions, and relationships through statistical summaries and visualisations.
* **Feature Engineering**: Converted categorical variables to a numerical format suitable for machine learning algorithms.
* **Model Selection and Training**: Four different regression models were trained and evaluated to find the best performer. The models included:
    * **Linear Regression**
    * **Decision Tree Regressor**
    * **Random Forest Regressor**
    * **XGBoost Regressor**
* **Model Evaluation**: Model performance was primarily measured using the R-squared ($R^2$) score.

## 4. Results
The models were evaluated based on their accuracy in predicting the number of flights. The $R^2$ scores for each model were:
* **Linear Regression**: 87.44%
* **Decision Tree Regressor**: 95.70%
* **Random Forest Regressor**: 99.88%
* **XGBoost Regressor**: 99.97%

The **XGBoost** and **Random Forest** models demonstrated superior performance, accurately capturing the complex patterns in the dataset.

## 5. How to Run
To replicate the analysis, you will need the following files:
* `Assignment 2.ipynb` (Jupyter Notebook with the code)
* `Flights.csv` (The dataset)

You can run the notebook by following these steps:
1.  Clone this repository to your local machine.
2.  Ensure you have Python installed with the necessary libraries (e.g., `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `xgboost`).
3.  Open the `Assignment 2.ipynb` file in a Jupyter environment.
4.  Run all cells in the notebook sequentially.
