# Credit Risk Classification Repository
This repository contains the code and analysis for credit risk classification using machine learning models. The goal of this analysis is to predict loan status, whether a loan would be classified as a healthy loan (0) or a high-risk loan (1), based on financial information.

## Contents
- credit_risk_classification.ipynb: Jupyter Notebook containing the analysis code, including data preprocessing, model training, and evaluation.                 
- Resources: Folder containing the dataset and resources used in the analysis.             
  - lending_data.csv: CSV file containing the loan data used in the analysis.

## Overview of the Analysis
The analysis in credit_risk_classification.ipynb is structured as follows:       

Data Preprocessing: The initial step involves handling missing values, encoding categorical variables, and splitting the data into training and testing sets to prepare the dataset for model training.           
Model Training: The primary machine learning model used in this analysis is the Logistic Regression. The model is trained using the training data.          
Model Evaluation: The trained model is evaluated using various performance metrics, such as accuracy, precision, and recall, to assess its effectiveness in predicting both healthy loans and high-risk loans.

## Results          
The analysis shows that the Logistic Regression model performed well in predicting loan status. The model achieved a balanced accuracy score of 0.95, indicating high overall accuracy. Moreover, the precision for both classes was relatively high, with a perfect precision of 1.00 for healthy loans and 0.86 for high-risk loans. The recall scores were also impressive, with a recall of 1.00 for healthy loans and 0.91 for high-risk loans, indicating that the model correctly identified the majority of instances for both classes.

## Summary and Recommendation             
Based on the results, the Logistic Regression model is strongly recommended for credit risk classification in this context. It demonstrates high accuracy, precision, and recall scores for both healthy loans and high-risk loans. However, the final recommendation may depend on the specific priorities and requirements of the business.             

Please note that this analysis is based on the provided dataset and a single machine learning model. Further exploration and model comparison may be necessary for more comprehensive insights.              
For any inquiries or further details, feel free to reach out.
