## Dataset

The dataset used in this project is the **Telco Customer Churn dataset**, which contains customer information for a telecom company. It includes demographic, subscription, and usage data that can be used to predict customer churn.

### Key Columns:

| Column Name           | Description |
|-----------------------|-------------|
| customerID            | Unique ID for each customer |
| gender                | Male or Female |
| SeniorCitizen         | Whether the customer is a senior citizen (0 = No, 1 = Yes) |
| Partner               | Whether the customer has a partner (Yes/No) |
| Dependents            | Whether the customer has dependents (Yes/No) |
| tenure                | Number of months the customer has stayed with the company |
| PhoneService          | Whether the customer has phone service (Yes/No) |
| MultipleLines         | Whether the customer has multiple lines (Yes/No/No phone service) |
| InternetService       | Type of internet service (DSL, Fiber optic, No) |
| OnlineSecurity        | Whether the customer has online security (Yes/No/No internet service) |
| OnlineBackup          | Whether the customer has online backup (Yes/No/No internet service) |
| DeviceProtection      | Whether the customer has device protection (Yes/No/No internet service) |
| TechSupport           | Whether the customer has tech support (Yes/No/No internet service) |
| StreamingTV           | Whether the customer streams TV (Yes/No/No internet service) |
| StreamingMovies       | Whether the customer streams movies (Yes/No/No internet service) |
| Contract              | Type of contract (Month-to-month, One year, Two year) |
| PaperlessBilling      | Whether the customer uses paperless billing (Yes/No) |
| PaymentMethod         | Payment method (Electronic check, Mailed check, Bank transfer, Credit card) |
| MonthlyCharges        | Amount charged per month |
| TotalCharges          | Total amount charged to the customer |
| Churn                 | Whether the customer churned (Yes/No) |

### Notes:
- The **Churn** column is the target variable.
- For privacy, a **sample dataset** is included in the `data/` folder.
- Original dataset can be downloaded from [Kaggle: Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
