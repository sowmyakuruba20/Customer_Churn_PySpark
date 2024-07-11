# Telecom Customer Churn Prediction
![screenshot](churn.png)
## Project Overview
The Telecom Customer Churn Prediction project aims to predict whether a customer will churn (leave the company) based on various features related to customer demographics, services subscribed, and account information. This project uses a dataset containing information about customers and their interactions with telecom services.

## Dataset Description
The dataset consists of 21 features, which include customer demographics, service details, and account information.
https://www.kaggle.com/datasets/sowmyakuruba/customer-churn-dataset

## Project Steps
1. Loading the Data

* Install necessary libraries.
* Import modules.
* Build Spark session.
* Load the dataset.
* Print the data schema and dimensions.

2. Exploratory Data Analysis (EDA)

* Perform distribution analysis.
* Conduct correlation analysis.
* Carry out univariate analysis.
* Identify missing values.
* Analyze numerical features using histograms.
* Generate a correlation matrix.
* Check unique value counts for categorical variables.
* Find the number of null values in the dataset.

3. Data Preprocessing

* Handle missing values using an Imputer.
* Remove outliers, particularly in the tenure column.

4. Feature Preparation

* Prepare numerical features:
  - Assemble feature vectors.
  - Scale numerical features.
* Prepare categorical features:
  - Index categorical features.
  - Assemble feature vectors.
* Combine numerical and categorical feature vectors.

5. Modeling and Evaluation

* Split the data into training and test sets.
* Train machine learning models.
* Evaluate model performance using appropriate metrics.
* Fine-tune models to improve performance.

## How to Run the Project
Clone the repository.
Install the necessary dependencies.
Run the Jupyter Notebook Customer_Churn_Prediction.ipynb to execute the project step-by-step.
Follow the instructions in each notebook cell to understand the process and replicate the analysis.

## Dependencies
Python 3.x
pyspark
pandas
numpy
matplotlib
seaborn
scikit-learn

## Conclusion
This project provides a comprehensive approach to predicting customer churn using machine learning techniques. By following the steps outlined in the notebook, you will be able to preprocess the data, explore key insights, and build predictive models to identify potential churners, allowing for proactive customer retention strategies.

Feel free to explore the notebook and modify the analysis to suit your specific needs. Happy analyzing! ​
