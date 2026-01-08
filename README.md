# 💳 Financial Transactions Fraud Detection System

## 📌 Project Overview
This project analyzes a dataset of **1+ million financial transactions** (2010s) to detect fraudulent activity. 
Using a **Random Forest Classifier**, the model identifies high-risk transactions with a focus on maximizing the "Recall" rate to catch as many fraudsters as possible.

**Key Challenge:** The dataset is highly imbalanced, with only **0.99%** of transactions being fraudulent.

## 📊 Key Insights
* **Fraud Rate:** 0.99% (Severe Class Imbalance)
* **High-Value Fraud:** Fraudulent transactions typically involve significantly higher amounts ($300+) compared to legitimate purchases.
* **Model Performance:** * The base Random Forest model achieved **~71% Recall** (Catch Rate).
    * By tuning the probability threshold to **0.30**, the Recall increased to **[Your New Number]%**, capturing significantly more fraud cases.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:** Pandas, Scikit-Learn, Seaborn, Matplotlib
* **Techniques:** SMOTE/Class Weights, Threshold Tuning, Star Schema Merging

## 📂 Project Structure
* `notebooks/`: Contains the step-by-step analysis (Data Merging -> EDA -> Modeling).
* `images/`: Visualizations of fraud patterns and confusion matrices.
* `models/`: Saved `.pkl` file of the trained model.

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/financial-fraud-analytics.git](https://github.com/YOUR_USERNAME/financial-fraud-analytics.git)
