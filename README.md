# E-Commerce Customer Churn Prediction

## Overview
This project focuses on predicting customer churn for an e-commerce company using data mining and machine learning techniques. Customer churn is a significant issue for e-commerce businesses as retaining existing customers is often more cost-effective than acquiring new ones. The goal of this project is to identify factors that influence customer churn and to develop a predictive model that can help the company take proactive measures to retain customers and improve profitability.

## Problem Statement
The main objective is to analyze the factors leading to customer churn and accurately predict churn using a machine learning model. By predicting customer churn, the company can enhance its customer retention strategies and improve long-term business performance. The project involves exploring the dataset, performing data preprocessing, implementing multiple machine learning models, and evaluating their performance.

## Data Sources
The dataset used for this project was sourced from [Kaggle](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction). It contains 5,630 records with 20 attributes related to customer behavior, demographics, and transaction details.

### Key Variables
- **custID**: Unique identifier for each customer
- **churnResult**: Indicator of customer churn (1 for churned, 0 for retained)
- **tenurePeriod**: Duration of customer association with the company
- **preferredLoginDevice**: Most frequently used device for login
- **warehouseToHome**: Distance from the warehouse to the customer's home
- **preferredPaymentMode**: Preferred payment method
- **Gender**: Customer's gender
- **hourSpendOnApp**: Average hours spent on the app or website
- **orderAmountHikeFromlastYear**: Percentage increase in order amount from the previous year
- **satisfactionScore**: Customer satisfaction rating (1-5)
- **Complain**: Indicates if the customer raised a complaint in the last month
- **couponUsed**: Number of coupons used in the last month

## Data Exploration and Preprocessing
The initial phase involved exploring the dataset to understand its structure and identify data quality issues. Key steps included:
- **Handling Missing Values**: Imputed missing values using the mean for continuous variables.
- **Correlation Analysis**: Conducted a correlation matrix to identify relationships between variables.
- **Data Visualization**: Utilized histograms and scatter plots to visualize trends and relationships.
- **Class Balance**: Analyzed the distribution of churn vs. non-churn classes to understand the dataset's balance.

## Data Mining and Modeling
The project implemented a variety of machine learning models to predict customer churn, including:
1. **Logistic Regression**: A baseline model for binary classification.
2. **Decision Tree**: Captured non-linear relationships between features.
3. **Random Forest**: An ensemble method that reduces overfitting risk.
4. **XGBoost**: A high-performance gradient boosting technique, providing the most accurate results.

### Model Evaluation
The models were evaluated using various metrics such as accuracy, precision, recall, F1-score, and ROC-AUC. Key results include:
- **Logistic Regression**: Accuracy of ~89% on the test dataset.
- **Random Forest**: Accuracy of ~97% on the test dataset.
- **Decision Tree**: Accuracy of ~95% on the test dataset.
- **XGBoost**: Highest performance with ~97% accuracy, demonstrating superior precision and recall.

## Results
The XGBoost model outperformed other models, making it the best choice for predicting customer churn in this dataset. This model's high accuracy and comprehensive evaluation metrics make it suitable for deployment in a real-world scenario to support business decisions.

## Conclusion
Predicting customer churn is a crucial strategy for enhancing customer retention in the e-commerce sector. The project successfully identified significant predictors of churn and developed a robust model for accurate churn prediction. By leveraging these insights, businesses can proactively address customer retention and optimize their operations.

## Future Work
Future improvements could include:
- Implementing additional feature engineering to capture more complex patterns in customer behavior.
- Experimenting with neural networks for potentially higher accuracy.
- Applying advanced hyperparameter tuning techniques for further model optimization.
- Incorporating more customer data to enhance model generalizability.

## Acknowledgements
The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction). Special thanks to the Data Mining in Engineering course at Northeastern University for guidance on this project.
