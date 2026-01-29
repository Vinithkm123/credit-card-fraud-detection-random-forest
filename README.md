# Credit Card Fraud Detection using Random Forest

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using a **Random Forest Classifier**.  
Fraud detection is a challenging task due to the **highly imbalanced nature of transaction data**, where fraudulent cases are rare compared to legitimate ones.

The project applies ensemble learning techniques to accurately identify fraud while minimizing false predictions.

---

## 🎯 Objective
- Detect fraudulent credit card transactions
- Handle imbalanced data effectively
- Compare Random Forest performance with a baseline Logistic Regression model
- Identify important features contributing to fraud detection

---

## 📊 Dataset
- **Name:** Credit Card Fraud (Synthetic Dataset)
- **File:** `credit_card_fraud_synthetic.csv`
- **Target Column:** `Class`
  - `0` → Non-Fraud
  - `1` → Fraud

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Joblib
- Google Colab
- GitHub

---

## 🔄 Workflow
1. Load and explore the dataset
2. Analyze class imbalance
3. Split data using stratified sampling
4. Train a baseline Logistic Regression model
5. Train Random Forest Classifier
6. Evaluate using Precision, Recall, and F1-score
7. Plot feature importance
8. Save trained model for reuse

---

## 📈 Model Used
### Random Forest Classifier
- Ensemble learning technique
- Reduces overfitting by averaging multiple decision trees
- Suitable for complex and imbalanced datasets

**Parameters:**
- `n_estimators = 100`
- `random_state = 42`

---

## 📊 Evaluation Metrics
Due to data imbalance, the following metrics were used:
- Precision
- Recall
- F1-score

Accuracy was not used as the primary metric.

---

## 📁 Project Structure
