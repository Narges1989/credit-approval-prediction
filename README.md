# Credit Card Approval Prediction
## Overview

Commercial banks receive a large number of credit card applications every day. Many of these applications are rejected for various reasons such as high loan balances, low income, or too many inquiries on an individual's credit report. Manually analyzing these applications is time-consuming, error-prone, and expensive. 

In this project, we aim to automate the process of credit card approval prediction using machine learning. This approach mimics the way real banks use machine learning to evaluate applications, increasing efficiency and accuracy. By the end of this project, you will have built an automatic credit card approval predictor using the power of machine learning.

## The Dataset

The dataset used in this project is a subset of the Credit Card Approval dataset from the UCI Machine Learning Repository. It contains credit card applications received by a bank, and the last column (`A16`) represents the approval status (target variable).

The dataset has both numerical and categorical features. Some features have missing values, denoted by a `?`, which we handle in the preprocessing step.

## File Structure

- `crx.data`: The dataset used for this project.
- `credit_card_approval_predictor.py`: Python script containing the full implementation of the credit card approval prediction model.

## Requirements

To run this project, you'll need the following Python packages:

- `pandas`
- `numpy`
- `scikit-learn`

You can install the required dependencies using `pip`:

```bash
pip install pandas numpy scikit-learn
