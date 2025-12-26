# customer-churn-analysis
# Customer Churn Analysis

## 📌 Project Overview
Customer Churn Analysis aims to predict whether a customer will leave a service based on historical customer data.  
This project focuses on data preprocessing, categorical encoding, and applying machine learning models for churn prediction.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 📊 Dataset Description
The dataset contains customer-related information such as:
- Demographics
- Service subscription details
- Account information
- Churn status (Target Variable)

---

## 🔄 Data Preprocessing Steps
1. Handling missing values  
2. Encoding categorical variables  
3. Feature scaling (Normalization / Standardization)  
4. Train-test split  

---

## 🔠 Encoding Technique Used: **Label Encoding**

### ✅ Why Label Encoding is Better Than One-Hot Encoding

In this project, **Label Encoding** is preferred over One-Hot Encoding for the following reasons:

- **Lower Dimensionality**  
  Label Encoding converts categories into a single numeric column, whereas One-Hot Encoding creates multiple columns, increasing feature count unnecessarily.

- **Efficient for Tree-Based Models**  
  Models like **Decision Tree**, **Random Forest**, and **XGBoost** work efficiently with label-encoded values and do not require one-hot encoded inputs.

- **Reduced Memory Usage**  
  One-Hot Encoding produces sparse matrices which consume more memory. Label Encoding keeps the dataset compact.

- **Faster Training Time**  
  Fewer features lead to faster model training and simpler computation.

### 🔁 Example
| Category | Label Encoded |
|--------|---------------|
| Yes    | 1             |
| No     | 0             |

---

## 🤖 Machine Learning Algorithms Used
- Decision Tree Classifier


---

## 📈 Model Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## ✅ Conclusion
Label Encoding proved to be more suitable than One-Hot Encoding for this customer churn dataset.  
It reduced feature dimensionality, improved computational efficiency, and worked effectively with tree-based machine learning models.

---

