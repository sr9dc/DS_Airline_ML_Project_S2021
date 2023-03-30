# Airline Customer Satisfaction Prediction

[R Documentation](sr9dc.github.io/DS_Airline_ML_Project_S2021/final_html.html)

This project is a machine learning-based analysis of customer satisfaction for airlines. We aim to identify the most economically-friendly factors that airlines can invest in to improve customer satisfaction. Our analysis is guided by the assumption that customer retention is intrinsically tied to customer satisfaction, and we use a Kaggle dataset comprising 25 columns and 130,000 observations to build predictive models that can help identify the key drivers of customer satisfaction.

## Project Overview
In this project, we create classifiers that can predict if a customer had a positive experience or a neutral/negative one. These models can then be leveraged to identify the factors that contribute most to customer satisfaction. We analyze two machine learning models: decision trees and random forests. In balancing their computational efficiency against their performance metrics, we provide a comprehensive audit of the ideal market model.

## Exploratory Data Analysis
We conducted exploratory analyses, supported by summary statistics and visualization, to gain a more comprehensive understanding of the dataset. We used the naniar package to evaluate how clean the dataset is and visualize any missing observations. We found that the dataset is fairly clean, with only a few missing values in the Arrival.Delay.in.Minutes column. We also summarized the features and analyzed their skew and metrics relative to each other.

## Fairness Assessment
To ensure that the dataset is comprehensive and representative of the protected classes it contains (Gender), we visualized the balance between Male and Female respondents. The data is fairly balanced, and satisfaction rates are nearly identical.

## Decision Tree Analysis
The first method we used to evaluate the dataset was a decision tree. Using CART, we built a binary classifier for identifying the most important factors in determining customer experience as either satisfied or not satisfied. We prepped the data for our decision tree by factoring categorical data while preserving numerical variables. The target variable, satisfaction, was verified and re-classified with 1 for satisfied and 0 for not satisfied.

# Conclusion
Our analysis of customer satisfaction for airlines using machine learning provides insights into the key factors that drive customer satisfaction. Our findings can be used to help airlines make data-driven decisions to improve customer satisfaction and retention.
