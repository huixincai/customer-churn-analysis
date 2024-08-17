
# Customer Churn Analysis Project

## Project Overview
This project aims to analyze customer churn in a telecom company, identify key factors contributing to churn, and develop predictive models to forecast churn. The insights derived from this analysis can help the company to strategize better customer retention plans and improve overall customer satisfaction.

## Dataset
The dataset used for this project [Kaggle](https://www.kaggle.com/datasets/rashadrmammadov/customer-churn-dataset). It includes various features related to customer demographics, account information, and service usage patterns.
## Key Features
- **CustomerID:** Unique identifier for each customer.
- **Gender:** Gender of the customer.
- **SeniorCitizen:** Indicates if the customer is a senior citizen.
- **Partner:** Indicates if the customer has a partner.
- **Dependents:** Indicates if the customer has dependents.
- **Tenure:** Number of months the customer has stayed with the company.
- **PhoneService:** Indicates if the customer has phone service.
- **MultipleLines:** Indicates if the customer has multiple lines.
- **InternetService:** Type of internet service the customer has.
- **OnlineSecurity:** Indicates if the customer has online security.
- **OnlineBackup:** Indicates if the customer has online backup.
- **DeviceProtection:** Indicates if the customer has device protection.
- **TechSupport:** Indicates if the customer has tech support.
- **StreamingTV:** Indicates if the customer has streaming TV.
- **StreamingMovies:** Indicates if the customer has streaming movies.
- **Contract:** Contract term of the customer.
- **PaperlessBilling:** Indicates if the customer uses paperless billing.
- **PaymentMethod:** Payment method used by the customer.
- **MonthlyCharges:** Monthly charges to the customer.
- **TotalCharges:** Total charges to the customer.
- **Churn:** Indicates if the customer churned.

## Data Analysis
The analysis involved exploring the distribution of various features and their relationship with customer churn. Key insights were derived from visualizations and statistical analysis.

### Key Insights
1. **Customer Demographics:**
   - Gender, senior citizen status, partner status, and dependents showed no significant impact on churn.

2. **Service Usage Patterns:**
   - Customers with no internet service had a higher churn rate.
   - Lack of online security, online backup, device protection, and tech support were associated with higher churn rates.

3. **Contract and Billing:**
   - Month-to-month contracts had lower churn rate.
   - Customers using electronic check and credit card payment method had higher churn rates.

## Predictive Modeling
Two machine learning models were developed to predict customer churn:
1. **Logistic Regression:**
   - Model Accuracy: 50%
   - Feature Importance: Tenure, DeviceProtection, TechSupport, Contract_Two year, PaymentMethod_Mailed check, OnlineSecurity_No.

2. **Random Forest:**
   - Model Accuracy: 50%
   - Feature Importance: MonthlyCharges, Tenure, TotalCharges, Contract_Month-to-month, Contract_Two year, PaymentMethod_Electronic check, OnlineSecurity_No, TechSupport_No, DeviceProtection_No.

## Business Insights
Based on the analysis and model results, the following recommendations are made:
1. **Address High Monthly Charges:** Reconsider pricing strategies and offer discounts or value-added services.
2. **Improve Long-term Customer Satisfaction:** Implement regular customer satisfaction surveys and proactive engagement.
3. **Enhance Service Offerings:** Promote services like online security, tech support, and device protection.
4. **Revise Contract Strategies:** Make long-term contracts more attractive and flexible.
5. **Target Specific Payment Methods:** Encourage stable and convenient payment methods like automatic bank transfers.

## Conclusion
This project demonstrates the application of data analysis and machine learning techniques to understand and predict customer churn in the telecom industry. The insights and models developed can help the company improve customer retention and satisfaction.

## Author
@huixincai  https://youtu.be/JhvfJYfjZuI

@rafaelperez @yezawei @khollah1 @whisperfool

## Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn


