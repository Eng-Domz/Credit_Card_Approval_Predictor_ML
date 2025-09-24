![Credit Card](./image/credit_card.jpg)


Commercial banks receive a lot of applications for credit cards. Many of them get rejected for many reasons, like high loan balances, low income levels, or too many inquiries on an individual's credit report, for example. Manually analyzing these applications is mundane, error-prone, and time-consuming (and time is money!). Luckily, this task can be automated with the power of machine learning and pretty much every commercial bank does so nowadays. In this workbook, you will build an automatic credit card approval predictor using machine learning techniques, just like real banks do.

## Approach

1. **Data Preprocessing**: Handle missing values and encode categorical variables
2. **Feature Engineering**: Use one-hot encoding for categorical features
3. **Model Training**: Train KNN and Logistic Regression models with cross-validation
4. **Model Comparison**: Compare performance and select the best model
5. **Evaluation**: Test on unseen data and measure accuracy

## Results
- **KNN Model**: 82.6% accuracy with optimal k=18
- **Logistic Regression**: 84.8% accuracy
- **Best Model**: Logistic Regression performs better in this dataset

