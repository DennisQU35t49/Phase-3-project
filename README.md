# Phase-3-project
# Customer Churn Prediction for Syriatel

## Overview

This project focuses on predicting customer churn for **Syriatel**, a leading telecommunications provider in Syria. *Customer churn*—when customers stop using a service—is a critical issue for the telecom industry. By understanding and addressing the factors that lead to churn, companies like Syriatel can significantly improve customer retention and drive revenue growth.

By leveraging machine learning, this project aims to develop a reliable churn prediction model and uncover actionable insights to guide Syriatel in its customer retention strategies.

---

![Syriatel Image](https://github.com/Michdev2024/Moringa-phase-3-project/blob/main/photo%202.jpg)

## Business Problem

To grow their revenue, telecommunication companies must not only attract new customers but also retain existing ones. Customer churn directly impacts the bottom line, with factors such as:

- Better pricing from competitors
- Poor service quality
- Lack of customer engagement

Recognizing that retaining existing customers is more cost-effective than acquiring new ones, **Syriatel** aims to:

1. *Predict customer churn* using historical data.
2. *Identify factors driving churn*, enabling actionable strategies to reduce it.

---

## Data Understanding

The dataset used in this project was sourced from [Kaggle's Churn in Telecoms Dataset](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset). 

### Dataset Highlights:
- *Rows (Customers)*: 3,333
- *Columns (Features)*: 21

### Feature Categories:
1. **Customer Information**: Basic details like demographics.
2. **Account Information**: Subscription and billing details.
3. **Usage Metrics**: Data on calls, minutes, and other usage behaviors.
4. **Customer Service Interaction**: Records of customer service calls.
5. **Target Variable**: A binary flag indicating whether a customer churned.

---

## Objectives

1. **Build a Machine Learning Model**: Develop and evaluate models to predict customer churn.
2. **Identify Key Features**: Pinpoint the most influential factors driving churn.

---

## Approach

1. **Exploratory Data Analysis (EDA)**: Explore the dataset to understand trends, distributions, and relationships.
2. **Feature Engineering**: Prepare and optimize features for modeling.
3. **Model Building**: Experiment with various machine learning models, including:
   - Baseline Model: Logistic Regression
   - Advanced Models: Decision Trees, Random Forest
4. **Model Tuning**: Optimize hyperparameters for improved performance.
5. **Evaluation**: Assess model performance using metrics such as accuracy and feature importance.

---

## Results and Key Insights

1. **Best Model**:
   - The **Random Forest** model achieved the highest predictive performance, outperforming Logistic Regression and Decision Trees.

2. **Key Predictive Features**:
   - *Total Day Minutes*
   - *Customer Service Calls*
   - *Subscription to International Plans*

3. **Significance**: These features provide actionable insights that can help Syriatel design targeted retention strategies for at-risk customers.

---

## Recommendations

1. **Enhance Customer Experience**:
   - Improve call quality by investing in advanced infrastructure and technology.
   - Streamline customer service operations to resolve issues promptly.

2. **Design Tailored Plans**:
   - Develop attractive international plans to retain subscribers with high international usage.

3. **Implement Proactive Retention Strategies**:
   - Offer personalized promotions and loyalty rewards to high-risk customers.

4. **Continuously Monitor Trends**:
   - Regularly update models and churn analysis to stay aligned with customer behavior and market dynamics.

---

## Conclusion

This project demonstrated how machine learning can be used to predict customer churn and derive actionable insights for improving customer retention. By leveraging predictive models, **Syriatel** can proactively identify at-risk customers and implement targeted strategies to improve retention and drive growth.
