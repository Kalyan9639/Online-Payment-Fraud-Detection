# 💳 Online Payment Fraud Detection using Machine Learning

## 📁 Project Overview:
This project focuses on developing a **fraud detection system** for online payment transactions using **Machine Learning** techniques. Fraud detection is crucial for financial institutions to protect their users and minimize financial losses.

We explore the dataset from **Kaggle** and apply supervised learning techniques to classify transactions as **fraudulent** or **legitimate**.

---

## 📊 Dataset Information :
- **Source:** [Kaggle](https://www.kaggle.com/datasets)  
- **Size:** Approximately **4.9 million** transaction records with 8 features.
- **Features:**
  - `step`: Time step (in hours)
  - `type`: Transaction type (e.g., CASH-IN, CASH-OUT, TRANSFER, etc.)
  - `amount`: Transaction amount
  - `oldbalanceOrg`: Sender's balance before the transaction
  - `newbalanceOrig`: Sender's balance after the transaction
  - `oldbalanceDest`: Recipient's balance before the transaction
  - `newbalanceDest`: Recipient's balance after the transaction
  - `isFraud`: Target variable (1 = Fraud, 0 = Legitimate)

---

## 🔍 Problem Statement :
The goal is to build a model that can accurately classify **fraudulent transactions** while minimizing false positives and false negatives. Fraud detection is a **high-stakes classification problem** where precision and recall are critical.

---

## 🧠 Machine Learning Approach :
### 1. Data Preprocessing
- Handled missing values and outliers. ( There are no missing values here )
- Applied **SMOTE** to balance the dataset.
- Engineered features to enhance model performance.

### 2. Model Building
- Algorithms Used:
  - **Logistic Regression**
  - **Random Forest Classifier**
- Addressed potential overfitting by removing leakage features.

### 3. Evaluation Metrics
- **Accuracy**
- **Precision, Recall, F1-Score**
- **ROC-AUC Score**
- **Cross-Validation** for robustness.

