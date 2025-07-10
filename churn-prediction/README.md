# Customer Churn Prediction

This project explores customer churn in a telecommunications company and uses machine learning to predict which customers are at risk of leaving. The goal is to help businesses proactively improve customer retention.
  
---
  
## Problem Statment
  
Customer churn is costly for service providers. Understanding *why* customers leave, and predicting *who* is most likely to churn, enables better-targeted retention strategies.
  
---

## Project Goals
  
- Identify key features that contribute to customer churn
- Build a predictive model to flag high-risk customers
- Compare model performance across multiple approaches
- Present clear, actionable insights with visualss

---

Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **pandas**, **seaborn**, **matplotlib**, **scikit-learn**
- **Github** (version control and sharing)

---

## Data Overview

The dataset includes over 7,000 customer records with features such as:

- Contract type
- Payment method
- Internet service
- Online security and backups
- Whether the customer churned (target)

The data was cleaned, preprocessed, and prepared for amchine learning. No major null or foriegn issues were found.

---

## Process Summary

1. **Exploratory Data Analysis (EDA0:**
- Visualized churn rates across multiple customer features
- Identified top predictors of churn (e.g., contract type, internet service, and online security)

2. **Model Building:**
- Trained a baseline logistic regression model
- Addressed class imbalance using class weights
- Trained and evaluated a Random Forest classifier

3. **Model Evaluation:**
- Accuracy, precision, recall, and F1-score
- Confusion matrix and classification reports
- Feature importance visualizations

---

## Results

| Model                 | Accuracy  | Churn Recall  | Churn Precision  |
| Logistic Regression   | 75%       | 55%           | 54%              |
| **Balanced Logistics  | 67.7%     | **87%**       | 45%              |
| **Random Forest**     | **73.8%** | **80%**       | **51%**          |

The **Random Forest model with class balancing** performed best overall, striking a strong balance between accuracy and the ability to catch churners.

---

## Key Visualizations

- Confusion Matrix
- Feature importance bar chart
- Precision/Recall/F1 bar chart for churn class

(Visuals are included in this file as PNG files.)

---

## Next Steps

- Experiment with oversampling (SMOTE) and tuning hyperparameters
- Try gradient boosting models for comparison
- Deploy the model using Flask or Streamlit for real-time predictions

---
