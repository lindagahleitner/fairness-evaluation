# Evaluating Bias Assessment & Mitigation Techniques in Machine Learning

The project aims to develop a predictive machine learning model using the AIF360 and DALEX toolkits to analyze the drug consumption dataset from the UCI Irvine Machine Learning Repository. The model will classify individuals into active and non-active drug users based on their reported usage of various substances. The primary target variable will categorize substances into four distinct groups: legal light drugs, party drugs, psychedelic drugs, and heavy drugs. Protected attributes such as gender, ethnicity, and personality scores will be examined to ensure the model's fairness and bias mitigation.

## Table of Contents
1. Use Case
2. Data used
3. Important Concepts
    - 3.1 Boundary between protected and unprotected attributes
    - 3.2 Understanding of the metrics
    - 3.3 Important metrics for our project
4. Fetching and preparing the dataset
    - 4.1 Fetching the dataset
    - 4.2 Data exploration
    - 4.3 Mapping the features to categorical meaning for readability
    - 4.4 Differentiate between active drug users and non-drug users
    - 4.5 Create drug categories to use as target variables for prediction
    - 4.6 One-Hot Encoding categorical features
5. Fairness Evaluation
    - 5.1 Setting protected attribute and target variable
    - 5.2 Splitting the dataset
    - 5.3 Learn 2 different classifiers (Logistic Regression and Random Forest) on original data
    - 5.4 Fairness evaluation with AIF360
    - 5.5 Fairness Evaluation with DALEX
6. Bias Mitigation AIF360
    - 6.1 Preprocessing algorithms
    - 6.2 In-processing algorithms
    - 6.3 Postprocessing algorithms
7. Bias Mitigation DALEX Fairness
    - 7.1 Preprocessing algorithms
    - 7.2 Postprocessing algorithms
8. Results
    - 8.1 Metric Summary Table & Interpretation for AIF360
9. Comparison AIF360 vs DALEX Fairness
    - 9.1 Features
    - 9.2 Usability
  
## Data 

The data used in this project was obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified). The dataset contains information about various personal and demographic attributes and their relation to drug consumption.

## Installation

1. Clone the repo
   ```s
   git clone https://github.com/lindagahleitner/fairness-evaluation.git
   
