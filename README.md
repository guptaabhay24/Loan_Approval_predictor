# 🏦 Loan Approval Detector

A Machine Learning project that predicts **whether a loan application should be approved or rejected** based on key applicant and financial parameters.  
Built using **Python** and a **Random Forest Classifier**, this model helps financial institutions automate and speed up the loan approval process while minimizing risk.

---

## 🚀 Features

- Predicts loan approval status based on applicant and financial details  
- Performs data cleaning, encoding, and normalization before model training  
- Uses **Random Forest Classifier** for high accuracy and reliability  
- Visualizes dataset insights using **Matplotlib** and **Seaborn**  
- Evaluates performance with **accuracy score**, **confusion matrix**, and **classification report**

---

## 🧩 Parameters Considered

The model analyses parameters like:
- Applicant Income  
- Co-applicant Income  
- Loan Amount  
- Loan Term  
- Credit History  
- Employment Type  
- Gender & Marital Status  
- Property Area (Urban / Semi-urban / Rural)  

---

## 🛠️ Tech Stack

**Languages & Libraries:**
- Python 3.x  
- pandas, numpy — data processing  
- seaborn, matplotlib — data visualization  
- scikit-learn — machine learning (RandomForestClassifier, train_test_split)  

**Tools:**
- Jupyter Notebook  
- Git & GitHub  

---

## 📊 Workflow

1. **Data Import** – Load dataset using `pandas.read_csv()`  
2. **Data Cleaning** – Handle missing values and encode categorical columns  
3. **Feature Engineering** – Select relevant predictors and target column  
4. **Train-Test Split** – Split data into training and test sets  
5. **Model Training** – Use `RandomForestClassifier` to train the model  
6. **Model Evaluation** – Evaluate accuracy, confusion matrix, and classification report  
7. **Visualization** – Plot correlations, distributions, and feature importance  

---

## ⚙️ How to Run Locally

```bash
# Clone the repository
git clone https://github.com/<your-username>/loan-approval-detector.git
cd loan-approval-detector

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook Finance.ipynb
