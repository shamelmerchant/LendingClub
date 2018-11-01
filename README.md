# Table of Contents
1. [Problem](README.md#problem)
2. [Input Dataset](README.md#input-dataset)
3. [Approach](README.md#approach)
4. [Dependencies](README.md#dependencies)

# Problem

Make a tool which can automatically predict 100 best investment opportunities to invest in LendingClub.

The ML model classify loans which might be defaulted and then selects the loans with highest return given lender criterions (Investment amount, Number of investments, time horizon etc)


# Input Dataset

The original dataset came from lending club https://www.lendingclub.com/info/download-data.action, we only used data from 2015 - 2018Q2 in this work.

The dataset consit of >1.5M loans with 146 features for each loan entry descrbing type of loan and financial characteristic of the person requesting the loan.

# Approach
1. Data aggregation and clean-up
2. Data imputation and feature engineering
3. Analyze variables and how they affect loan_status
4. Machine Learning model to classify bad loans
5. Subselection tool for selecting loans #TODO (Not implemented yet)

# Dependencies
- Python3
