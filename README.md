# 📊 Telco Customer Churn Predictor

An end-to-end machine learning workflow built in Google Colab that identifies high-risk subscribers using operational and billing data. This project translates raw customer data into actionable business intelligence to drive retention strategies.

[![Open In Colab]](https://colab.research.google.com/drive/1nkVSoFhm2gex7_sfFJcbVwpPdj2iZBjc?usp=sharing).

## 🎯 Project Overview
Customer churn directly impacts predictable revenue. This project builds a predictive pipeline to catch churning customers before they cancel their subscriptions. 

* **The Data:** Cleaned and preprocessed over 7,000 subscriber records, handling missing values, structural anomalies, and categorical text encoding.
* **The Model:** Trained an ensemble **Random Forest Classifier** to map complex combinations of tenure lengths, monthly charges, and contract types to churn outcomes.
* **The Impact:** Created a scalable framework for a business to proactively target at-risk users with retention offers, prioritizing high-value accounts.

## 🛠️ Tech Stack & Skills
* **Environment:** Google Colab
* **Data Engineering:** Python, Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest, Train/Test Split)
* **Evaluation Metrics:** Classification Reports (Precision, Recall, F1-Score)

## 📈 Key Business Insights
* Financial metrics like **Monthly Charges** and **Contract Type** emerged as the strongest leading indicators of customer defection.
* Transitioning month-to-month subscribers to longer-term agreements represents the single highest-leverage retention opportunity.
