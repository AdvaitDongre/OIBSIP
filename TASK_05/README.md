# Sales Prediction Readme

## Overview
This repository contains a Python script for sales prediction using linear regression. The analysis focuses on understanding the relationships between advertising channels (TV, Radio, Newspaper) and product sales. The linear regression model is built and evaluated to provide insights into the impact of each advertising channel on sales.

## Requirements
Ensure you have the following Python libraries installed:
- numpy
- pandas
- seaborn
- matplotlib
- statsmodels
- scikit-learn

## Data
The dataset used for analysis is provided in the "Advertising.csv" file. It includes information on advertising spending in different channels (TV, Radio, Newspaper) and the corresponding sales.

## Exploratory Data Analysis (EDA)
- The initial exploration involves loading the dataset, renaming columns, and performing basic data summary and visualization.
- Pair plots and correlation matrices provide visual insights into the relationships between variables.
- Key observations:
  - Positive correlation between TV and Radio with Sales.
  - Limited impact of Newspaper on Sales.
  - Distribution of variables is examined through histograms.

## Model Training
- The data is split into training and testing sets.
- A linear regression model is trained using the Ordinary Least Squares (OLS) method from the statsmodels library.
- Model summary includes R-squared, coefficients, and statistical significance.

## Model Evaluation
- The script includes model evaluation metrics such as Mean Squared Error (MSE) and R-squared.
- The model is further validated using cross-validation and grid search.

## Predictions
- Predictions are made using the trained model for sample data.

## Usage
1. Ensure you have the required libraries installed.
2. Clone the repository: `git clone https://github.com/your-username/sales-prediction.git`
3. Navigate to the project directory: `cd sales-prediction`
4. Run the Python script: `python sales_prediction.py`

## Conclusion
The analysis provides valuable insights into the impact of advertising channels on sales. The linear regression model highlights the significance of TV and Radio advertising, while Newspaper advertising shows minimal impact. These findings can guide future marketing strategies.

Happy analyzing!
