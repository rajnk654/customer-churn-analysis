
---

## 🧪 Dataset Information
- **Dataset Name:** Telco Customer Churn Dataset
- **Description:**  
  The dataset contains customer demographics, service usage information, billing details, and churn status.
- **Target Variable:** `Churn`
- **Use Case:** Customer retention and churn prediction

---

## 🔧 Data Preprocessing Steps
The following preprocessing steps are performed in this repository:

###  Data Loading
- Loaded the CSV dataset using **Pandas**
- Verified data structure and dimensions

### Data Inspection
- Checked column names and data types
- Identified missing and inconsistent values

### Handling Missing Values
- Cleaned null values
- Converted incorrect data types where necessary


### Encoding Categorical Variables
- Applied **Label Encoding**
- Applied **One-Hot Encoding** where required

### Feature Scaling
- Applied **Standard Scaling (Z-Score Normalization)**
- Scaling performed **after train-test split** to prevent data leakage
- Scaled numerical features:
  - `tenure`
  - `MonthlyCharges`
  - `TotalCharges`

---

## ⚙️ Feature Scaling Technique
**StandardScaler** from `sklearn.preprocessing` was used:

- Mean = 0
- Standard Deviation = 1
- Improves model performance and convergence

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/rajnk654/customer-churn-analysis.git
