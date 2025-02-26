# Financial Data Mining for Customer Targeting in Banking

## Executive Summary
This project applies data mining techniques to analyze banking data from a Portuguese financial institution. The objective is to predict customer behavior and improve targeted marketing strategies using predictive modeling. By leveraging SAS Enterprise Miner, the study employs the SEMMA framework (Sample, Explore, Modify, Model, and Assess) to extract meaningful insights from historical marketing campaign data.

## Business Problem
Financial institutions face challenges in **customer segmentation and credit risk management**, making it difficult to optimize marketing strategies. Traditional credit scoring models have limitations in predicting customer behavior effectively. This study aims to identify key factors influencing customer subscription to term deposits and improve marketing efficiency.

## Methodology
- **Data Exploration**: Examined dataset structure, missing values, skewness, and distribution.
- **Data Processing**: Applied data transformation, imputation of missing values, and feature selection.
- **Modeling**: Developed and evaluated multiple predictive models including Logistic Regression and Decision Trees.
- **Performance Evaluation**: Used key performance metrics such as ROC Index, Cumulative Lift, and Classification Accuracy to determine the best model.

## Key Findings
- **The Decision Tree Multi-way Split (Tree3way)** model emerged as the best-performing model with an ROC Index of 0.87 and a high predictive accuracy.
- Customers with higher engagement duration, certain job categories (e.g., retirees), and specific previous interactions were more likely to subscribe to term deposits.
- The dataset was imbalanced, requiring stratified sampling to improve model reliability.

## Business Recommendations
- **Utilize Predictive Models for Targeted Marketing**: Implement the Decision Tree Multi-way Split model in marketing campaigns to focus on high-potential customers.
- **Enhance Customer Segmentation**: Use insights from the model to create customer profiles based on their likelihood to subscribe.
- **Optimize Communication Strategies**: Prioritize contacting customers in months with historically high subscription rates and tailor outreach based on past interactions.
- **Improve Data Quality**: Address missing data issues in future datasets to enhance model accuracy and reliability.
- **Monitor Model Performance**: Regularly retrain and evaluate models to adapt to changing customer behaviors.

## Next Steps
- **Deploy the Model**: Integrate the decision tree model into a bank’s customer relationship management (CRM) system for real-time predictions.
- **Feature Expansion**: Explore additional features such as social media interactions or real-time financial transactions to improve predictive accuracy.
- **A/B Testing**: Conduct live testing of the model’s recommendations in marketing campaigns to measure effectiveness.
- **Scalability & Automation**: Develop automated workflows for continuous model retraining and performance monitoring.

By applying data mining techniques effectively, financial institutions can enhance customer targeting, improve marketing ROI, and increase subscription rates for financial products.

## Technology & Tools Used
SAS Enterprise Miner
