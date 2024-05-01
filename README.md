# MAHW3

# Telco Customer Churn Prediction and Survival Analysis

## Project Overview
This project focuses on analyzing customer churn for a telecommunications company using survival analysis techniques. By applying statistical models to predict the time until a customer churns, we aim to provide actionable insights that can help in devising effective customer retention strategies.

## Data Description
The dataset, `telco.csv`, includes various attributes of customers such as region, tenure, age, marital status, service subscriptions, and churn status. The primary objective is to use this data to model customer churn and calculate Customer Lifetime Value (CLV).

## Files
- `telco.csv`: The primary dataset containing customer information.
- `survival_analysis.ipynb`: Jupyter notebook containing all the code and analysis.
- `requirements.txt`: A text file listing the libraries needed to run the project.

## Models Used
- **Weibull AFT Model**: Provides estimates on the survival function based on a Weibull distribution.
- **Log-Normal AFT Model**: Models the survival times using a log-normal distribution.
- **Log-Logistic AFT Model**: Utilizes a log-logistic distribution to estimate the survival function.

Each model provides a different perspective and fit to the data, allowing for comprehensive insights into customer behavior over time.

## Setup and Installation
To run this project, Python 3.x is required along with the following libraries:
- pandas
- numpy
- matplotlib
- lifelines

You can install all required packages using the following command:
```bash
pip install -r requirements.txt
