<img src="header.jpg" alt="Repo Header"/><br/>

# Classification - Credit Card Default Predictor

![GitHub last commit](https://img.shields.io/github/last-commit/smartbre/credit-default)<br/>

**Authors**: Brent Smart

## Overview

This project analyzes credit card payment history of customers of a Taiwanese credit card company from April 2005 - September 2005 in order to build a model that predicts whether or not an active customer will default on their line of credit. A customer's default represents lost income. The amount of a customer's sixth bill before they default represents a cost to the company. In this analysis customers' default cost this credit card company NT$ 306,733,698. The credit card company can use this predictive model to adjust outreach, resources, and approval for lines of credit.

## Business Problem

The company will be able to predict with 80% accuracy whether or not a customer will default on their line of credit. Doing so will help the company identify potential defaulters in order to evaluate the risk associated with doing business with that customer.

## Data

This project uses the "Default of Credit Card Clients Data Set" from the UCI Machine Learning Repository. The dataset provides payment history, some demographic data (sex, education, etc.), in addition to information on whether each customer will default on their line of credit for 30,000 customers. There are 23439 active card users. Hence, all features were used included in this analysis.


## Modeling

The final model with the target variable Default_Next_Month includes all original columns. 

## Evaluation

The model underwent multiple interactions, each time investigating how well the model addressed Accuracy, Recall, and Precision. Accuracy was emphasized to prevent misidentify defaulting customers. At the end the final model showed overall improvement in accuracy. 


## For More Information

Please review our full analysis in [our Jupyter Notebook](./credit_default/notebooks/report/Classification - Credit Card Default Prediction (Models Notebook).ipynb) or our [presentation](./credit_default/reports/Phase 3_ Classification Models - Credit Card Default Prediction.pdf).

For any additional questions, please contact **Brent Smart smartbrent1@gmail.com**

## Repository Structure

```
├── README.md        <-- Main README file explaining the project's business case,
│                        methodology, and findings
│
├── data             
│   └── raw          <-- Data in excel format
│
├── notebooks        <-- Jupyter Notebooks for exploration and presentation
│   ├── exploratory  <-- Unpolished exploratory data analysis (EDA) notebooks
│   └── report       <-- Polished final notebook(s)
│
└── reports          <-- Generated analysis (including presentation.pdf)
    └── figures      <-- Generated graphics and figures to be used in reporting
