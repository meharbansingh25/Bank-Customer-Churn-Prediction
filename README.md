# Bank Customer Churn Prediction

---

## Tools Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Overview

This project focuses on predicting customer churn using machine learning techniques. The objective is to identify customers who are likely to leave the bank and understand the key factors influencing churn behavior.

The project starts with raw customer data and includes data cleaning, exploratory data analysis (EDA), statistical analysis, feature engineering, data preprocessing, customer segmentation using K-Means Clustering, and predictive modeling using multiple machine learning algorithms.

---

## Project Workflow

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Feature Engineering
* Data Preprocessing
* Logistic Regression
* Decision Tree
* Random Forest
* Model Comparison
* Model Interpretation
* K-Means Clustering
* Business Insights
* Final Conclusion

---

## Libraries Used

* Pandas for data analysis and manipulation
* NumPy for numerical computations
* Matplotlib and Seaborn for data visualization
* Scikit-learn for machine learning and clustering algorithms

---

## Feature Engineering

The following new features were created from the raw dataset:

* Age Group

  * Young
  * Adult
  * Senior

* Credit Category

  * Poor
  * Average
  * Good

* Balance Category

  * Zero Balance
  * Low Balance
  * Medium Balance
  * High Balance

These engineered features helped improve customer behavior analysis and model interpretation.

---

## Machine Learning Models

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

## Model Comparison (Churn Class Performance)

|Model                 |   Accuracy    |    Precision     |    Recall     |    F1 Score  |
|----------------------|---------------|------------------|---------------|--------------|
|Logistic Regression   |   81.6%       |    59%           |     22%       |    32%       |
|Decision Tree         |   78.2%       |    45%           |     50%       |    47%       |
|Random Forest         |   86.9%       |    77%           |     48%       |    59%       |

---

## K-Means Customer Segmentation

Customer segmentation was performed using K-Means Clustering.

The Elbow Method was used to determine the optimal number of clusters.

The clustering process identified multiple customer segments with different churn behaviors, helping the bank understand customer risk profiles more effectively.

---

## Key Insights

* Germany recorded the highest customer churn rate.
* Senior customers were more likely to churn.
* Inactive customers showed significantly higher churn behavior.
* Customers with poor credit profiles were more likely to leave the bank.
* Age was one of the most important factors influencing churn.
* Customer activity status strongly impacted churn probability.
* K-Means clustering identified a high-risk customer segment.
* Random Forest achieved the highest prediction accuracy among all models.

---

## Business Recommendations

* Focus retention campaigns on senior customers.
* Improve engagement strategies for inactive customers.
* Monitor high-risk customer segments identified through clustering.
* Strengthen customer retention efforts in high churn regions.
* Use predictive models to identify churn-prone customers early.
* Offer personalized products and services to improve customer loyalty.

---

## Model Interpretation

Random Forest Feature Importance analysis showed that the following factors had the strongest influence on churn prediction:

* Age
* Estimated Salary
* Credit Score
* Number of Products
* Balance
* Customer Activity Status

These features played a major role in determining whether a customer was likely to leave the bank.

---

## Churn Distribution

![Churn Distribution](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/01_Customer_Churn_Distribution.png)

---

## Geography vs Churn

![Geography vs Churn](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/03_Geography_vs_Churn.png)

---

## Age vs Churn

![Age vs Churn](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/06_Age_vs_Churn.png)

---

## Model Comparison

![Model Comparison](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/09_Model_Comparison.png)

---

## Random Forest Feature Importance

![Feature Importance](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/11_Random_Forest_Feature_Importance.png)

---

## K-Means Elbow Method

![Elbow Method](https://github.com/meharbansingh25/Bank-Customer-Churn-Prediction/blob/main/Bank%20Customer%20Churn%20Prediction/Images/12_Elbow_Method.png)

---

## Conclusion

This project successfully analyzed customer churn behavior using data analysis, customer segmentation, and machine learning techniques.

Multiple machine learning models were trained and evaluated, with Random Forest achieving the best performance at 86.9% accuracy.

The project demonstrates how machine learning can help banks identify high-risk customers, understand churn drivers, and support proactive customer retention strategies.
