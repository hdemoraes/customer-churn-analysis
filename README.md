📊 Customer Churn Risk Analysis and Retention Insights
Overview

This project analyzes customer churn behavior using a real-world telecom dataset. The goal is to identify high-risk customers and provide actionable strategies to improve retention.

🔍 Problem

Customer churn is a major challenge in subscription-based businesses. This project addresses:

Why customers churn

Who is most likely to churn

How to reduce churn using data

⚙️ Methodology

Data Cleaning

Handled missing values in TotalCharges

Converted data types for analysis

Exploratory Data Analysis (EDA)

Identified key churn drivers:

Contract type

Tenure

Monthly charges

Service type

Feature Engineering

One-hot encoding for categorical variables

Train/test split

Feature scaling

Modeling

Logistic Regression

Accuracy: ~78%

Recall (churn): ~52%

Customer Segmentation

High Risk (>70%)

Medium Risk (40–70%)

Low Risk (<40%)

📈 Key Insights

Month-to-month customers have the highest churn

New customers (low tenure) are more likely to leave

Higher monthly charges increase churn probability

Fiber optic users show higher churn rates

💡 Business Recommendations

Target high-risk customers with retention incentives

Improve onboarding experience in first 3–6 months

Encourage long-term contracts

Review pricing strategy

🧠 Business Impact

This project enables:

Proactive churn prevention

Better allocation of retention budget

Data-driven decision making

🛠️ Tools Used

Python (Pandas, Scikit-learn, Seaborn)

Google Colab

📂 Dataset

Telco Customer Churn Dataset

🚀 Future Improvements

Threshold tuning for better recall

Advanced models (Random Forest, XGBoost)

Dashboard (Streamlit / Power BI)
