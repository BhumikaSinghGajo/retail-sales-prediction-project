
# ML Retail sales Prediction project 

The code and documentation for the Rossman Sales Prediction project are located in this repository. This project aims to forecast Rossmann stores' daily sales up to six weeks ahead of time. Store managers can make well-informed decisions about promotions, competition, holidays, and other factors that impact sales performance by accurately forecasting sales. 


## Problem Statement:

Rossmann operates over 3,000 drug stores in 7 European Countries. Currently, Rossmann store managers are tasked with predicting their daily sales up to six weeks in advance. Store sales are influenced by many factors, including promotions, competition, school and state holidays, seasonality, and locality. With thousands of individual managers predicting sales based on their unique circumstances, the accuracy of results can be quite varied. You are provided with historical sales data for 1,115 Rossmann stores. The task is to forecast the 'Sales' column for the test set. Note that some stores in the dataset were temporarily closed for refurbishment
## Project Summary:

To accurately forecast sales, the Rossman Sales Prediction project required a great deal of feature engineering, data analysis, and model selection. Below is a quick summary of the project's phases and main conclusions: 

**1. Data collection and Cleaning**

* gathered historical sales information for Rossmann stores, including information about competitors, holidays, customers, and daily sales

* guaranteed data integrity by cleaning and preparing the dataset for analysis.

* addressed outliers and missing values to raise the data's quality.

**2. Exploratory Data Analysis (EDA)**

* conducted thorough EDA to examine univariate, bivariate, and multivariate relationships in order to glean insightful information from the data set.

* created perceptive data visualizations to identify trends and patterns.

* derived significant insights to guide machine learning pipeline decision-making in the future.

**3. Feature Engineering and Preprocessing**

* In order to gather crucial data, new features like PromoDuration and Competition Distance were engineered.

* Variance inflation factor (VIF) analysis was used to address multicollinearity among independent variables.

* Outliers were identified and dealt with by applying the Interquartile Range (IQR) method.

* To make categorical variables compatible with machine learning algorithms, One-Hot Encoding was applied.

* used a variety of transformation methods to get the data to have a normal distribution.

**4. Model Selection and Training**

* To assess the performance of the model, divide the preprocessed data into training and testing sets.

* Use regression techniques to implement a variety of machine learning algorithms, such as decision trees, random forests, and linear regression.

* measured the performance of the model using metrics like root mean square error, means square error, and R-squared score.

* used regularization strategies to improve model performance, such as Lasso, Ridge, and Elastic Net.

**5. Conclusion**

* Following extensive testing with different machine learning models, the best-performing model for sales prediction was found to be XGBoost.

* On the training dataset, it maintained an impressive R2 score of 97%, and on the test dataset, it reached an even more impressive 98%**.

* In comparison to other models, the model's Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) values were lower, indicating higher predictive accuracy.

* Robust generalization is suggested by consistent performance across several evaluation metrics, such as the R2 score, MSE, and RMSE.

* Well-behaved residuals with mean and median values near zero were found by residuals analysis, confirming the model's ability to successfully capture underlying data patterns.

  This project demonstrates how to use machine learning, feature engineering, and data analysis to effectively solve a real-world forecasting problem. The analysis's conclusions offer insightful data that is helpful for retail decision-making. 
