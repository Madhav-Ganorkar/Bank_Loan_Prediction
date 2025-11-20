# 📄 Loan Approval Prediction – Machine Learning Project

## 🏦 Project Overview
This project predicts whether a loan should be **approved or rejected** using machine learning.  
It includes the complete end-to-end ML workflow:

- Data Cleaning  
- Missing Value Handling  
- Outlier Detection (Z-Score / IQR based on skewness)  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Encoding  
- Scaling  
- Model Building  
- Evaluation  
- Feature Importance Analysis  

---

## 📁 Dataset Information
The dataset includes:

- Loan Id
- No. of Dependents
- Education
- Self Employed
- Income Annum
- Loan Amount
- Loan Term
- Cibil Score
- Residential Assets Value
- Commercial Assets Value
- Luxury Assets Value
- Bank Asset Value  
- Loan Status (Target)

**Target Variable:** `Loan_Status`  
- 1 = Approved  
- 0 = Rejected  

---

# ⚙️ Project Workflow

## ✔ 1.🧹 Data Loading & Inspection
- Load dataset  
- Check shape, types, missing values
  
---

## ✔ 2.🔍 Exploratory Data Analysis (EDA)
- Countplots for categorical variables   
- Correlation heatmap 

---

## ✔ 3.📊 Outlier Detection & Treatment
Outliers were detected using:

- Histogram  
- KDE Plot  
- Boxplot  
- Skewness  

### 📌 Outlier Logic:
- If **|skewness| < 0.5** → **Normal** → Z-Score  
- If **|skewness| > 0.5** → **Skewed** → IQR  

---

## ✔ 5.🛠 Feature Engineering
- Label Encoding for categorical columns  
- StandardScaler for numerical columns  

---

## ✔ 6.🤖 Model Building
Model used:

### ➤⭐ Logistic Regression  
Simple, interpretable, works well for binary classification.

---

## ✔ 7.🧪 Model Evaluation
Metrics used:

- Accuracy  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1)  

---

## ✔ 8.🌟 Feature Importance Analysis
Methods used:

### **Logistic Regression Coefficients**  
Shows positive/negative effect on loan approval.

Top contributors usually include:

- Income_Annum
- Loan Term    

---

# 📈 Key Insights 
- Higher income positively impacts approval.  
- Large loan amounts reduce approval chances.  
- Demographic attributes (No of Dependents) contribute minimally.  

---

# 🚀 Technologies Used

- 🐍 Python  
- 📊 Pandas, NumPy  
- 🎨 Matplotlib, Seaborn  
- 🤖 Scikit-Learn  
- 📝 Google Colab / Jupyter Notebook   

---

# 📂 Project Structure
Loan_Prediction/
│── loan_approval_dataset.csv
│── Loan_Prediction.ipynb
│── README.md


---

# 🏁 Conclusion
This project demonstrates a complete workflow for predicting loan approvals using machine learning.  
It follows industry-level data preprocessing, EDA, outlier handling using skewness logic, modeling, and feature importance.

Suitable for:
- ML Learning  
- Data Science Case Studies

---

## 👤 Author
- **Madhav Ganorkar**  
- Contact: [LinkedIn](https://www.linkedin.com/in/madhav-ganorkar)

---




