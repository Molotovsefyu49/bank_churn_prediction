
# Bank Customer Churn Analysis

This repository contains an analysis of bank customer churn using machine learning techniques. The goal of this project is to understand factors that contribute to customer churn and to develop predictive models to identify customers at risk of churning.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Results](#models-and-results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company. In the context of a bank, churn occurs when customers close their accounts or switch to another bank. Understanding and predicting customer churn is crucial for businesses to take proactive measures to retain customers.

This project includes data preprocessing, exploratory data analysis, feature engineering, model training and evaluation, and interpretation of results.

## Dataset

The dataset used in this project contains customer information including demographic details, financial history, and engagement with the bank's products. The main columns include Age, Gender, Balance, CreditScore, EstimatedSalary, NumOfProducts, HasCrCard, IsActiveMember, Tenure, and Exited (target variable indicating churn).

## Installation

To run the analysis and models in this project, you will need Python 3.x and several libraries. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

## Usage

1. Clone this repository:

```bash
git clone https://github.com/
Molotovsefyu49/bank-churn-prediction.git
cd bank-churn-prediction
```

2. Install the required libraries as mentioned above.

3. Open and explore the Jupyter Notebook files (.ipynb) in the `notebooks` directory. These notebooks contain the step-by-step analysis, data preprocessing, modeling, and visualization.

4. Execute the code cells in the notebooks to replicate the analysis and results.

## Models and Results

The project includes the implementation and evaluation of multiple machine learning models, including Logistic Regression, Random Forest, Gradient Boost, and Light GBM. The evaluation metrics such as accuracy, precision, recall, F1-score, and ROC AUC are used to assess the performance of the models.

The feature importance analysis is performed to understand which features have the most significant impact on predicting customer churn.

## Contributing

Contributions are welcome! If you find any issues or improvements, please create a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```
