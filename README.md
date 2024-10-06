# Telecom Customer Churn Prediction Capstone Project

## Overview

This capstone project aims to analyze customer churn in a telecommunications company providing home phone and internet services to 100,000 customers in Southeast Asia. The company has observed a significant increase in customer churn and seeks to identify the reasons behind it and reduce the loss of high-value customers who contribute 80% of total revenue.

## Data Description

The dataset contains approximately 100,000 observations and 225 features. Key features include:

- **Recharging of the Service:**
  - `av_rech_amt_data`: Average recharge data amount
  - `count_rech_2g`: Count of 2G recharges
  - `count_rech_3g`: Count of 3G recharges
  - `max_rech_data`: Maximum recharge for mobile internet
  - `total_rech_data`: Total recharge for mobile internet
  - `max_rech_amt`: Maximum recharge amount
  - `total_rech_amt`: Total recharge amount
  - `total_rech_num`: Total number of recharges

- **Call and Internet Service:**
  - `total_calls_mou`: Total minutes of voice calls
  - `total_internet_mb`: Total amount of internet usage in MB
  - `arpu`: Average revenue per user
  - Various metrics for incoming/outgoing calls.

- **Categorical Variables:**
  - `night_pck_user`: Prepaid service schemes for night usage
  - `fb_user`: Service scheme for Facebook and similar platforms

The dataset also includes variables for four different months, indicated by suffixes `.6`, `.7`, `.8`, and `.9`.

## Problem Statement

The objective of this project is to predict churn in the ninth month using data from the previous three months. Key goals include:

- Identifying variables affecting customer churn.
- Defining high-value customers and predicting churn specifically for this group.
- Building machine learning models to predict churn and identify important variables.

## Solution Roadmap

The project follows these key steps:

1. **Import Libraries and Load Dataset**: Set up the environment and load the dataset.
2. **Data Exploration and Preprocessing**:
   - Analyze data types and handle missing values.
   - Identify relevant data for the problem.
3. **Feature Engineering**:
   - Extract new relevant features.
   - Define high-value customers.
   - Derive the target variable "churn".
4. **Data Visualization**: Use visualizations to extract insights and identify outliers.
5. **Modeling**:
   - Split data into training and testing sets.
   - Handle class imbalance and build machine learning models.
   - Evaluate model performance and optimize hyperparameters.
6. **Business Insights and Recommendations**:
   - Identify important predictor attributes and visualize them.
   - Compute misclassification costs and recommend churn management strategies.

## Business Insights and Recommendations

1. **Churn Analysis**: Utilize logistic regression or tree-based models to identify predictors of churn. Visualize these predictors to convey feature importance.
2. **Misclassification Costs**: Calculate baseline misclassification costs and explore how they vary with different classification cut-offs. Propose strategies to manage churn based on insights gained.
3. **NLP for Customer Interactions**:
   - Analyze customer feedback using NLP techniques to predict churn.
   - Leverage LLMs and recent advancements in AI for innovative solutions.
   - Implement a real-time customer feedback system and proactive engagement strategies.

## Conclusion

This project aims to provide actionable insights to the telecom company, allowing them to effectively reduce churn and enhance customer retention, particularly among high-value customers. By combining machine learning with real-time customer feedback analysis, the company can develop tailored strategies to engage and retain customers.

## Getting Started

To run the project:

1. Download the dataset and data dictionary from the provided link.
2. Upload the dataset to your Google Drive.
3. Use Google Colab to write and execute Python code.
4. Follow the solution roadmap to implement the project steps.

## Data Set 
-https://drive.google.com/file/d/1uW28ofpGlfsvksfKIdlLDMyaG0YZ2eCU/view?usp=drive_link

## References

- Customer Churn Prediction System based on Self-Attention
- Churn prediction using multimodality of text and tabular features with Amazon SageMaker Jumpstart
