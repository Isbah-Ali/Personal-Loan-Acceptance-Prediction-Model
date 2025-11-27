# Personal Loan Acceptance Prediction

Predicting which customers are likely to accept a personal loan offer using the **Bank Marketing Dataset (UCI Machine Learning Repository)**.

---

## 📌 Project Overview

This machine learning project analyzes customer demographics and financial attributes such as **age**, **job**, **marital status**, **loan history**, and **campaign contact details** to predict whether a customer will accept a **personal loan offer**.

Two classification models were trained:

- **Logistic Regression**
- **Decision Tree Classifier**

The goal is to help banks target potential customers more effectively.

---

## 📂 Dataset

**Source:** Bank Marketing Dataset — UCI Machine Learning Repository  
**File:** `bank-full.csv`  
**Separator:** Semicolon (`;`)

**Target Variable:**  
- `y` → `1` = accepted loan  
- `y` → `0` = did not accept

---

## 🔧 Data Preprocessing

Steps performed:

- Loaded dataset using pandas  
- Encoded all categorical columns using `LabelEncoder`  
- Split dataset into **Train (80%)** and **Test (20%)**  
- Standardized features for Logistic Regression using `StandardScaler`

---

## 🧠 Models Used

### 1️⃣ Logistic Regression
- Provides probability of acceptance  
- Good for linear relationships  
- Easy interpretability through coefficients

### 2️⃣ Decision Tree Classifier
- Captures non-linear patterns  
- Provides **feature importance**  
- Useful for business insights

---

## 📈 Evaluation Metrics

For both models, the following metrics were computed:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**
- **ROC-AUC Score**
- **Confusion Matrix**

These help compare which model performs better.

---

## ⭐ Key Insights

From Decision Tree feature importance & Logistic Regression coefficients:

- Customers with **longer call duration** are more likely to accept.  
- **Previous successful marketing outcomes** increase acceptance probability.  
- **Type of contact** (cellular vs telephone) matters.  
- **Age**, **job type**, and **marital status** show noticeable trends.  
- **Education and housing loan status** also affect acceptance.

These insights help banks optimize **targeted marketing campaigns**.

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Author

Isbah Ali - Data Analyst
