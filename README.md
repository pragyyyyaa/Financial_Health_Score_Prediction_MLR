# Financial Health Prediction using Multiple Linear Regression

## 📌 Project Overview
This project predicts the **Financial Health Score** of companies using **Multiple Linear Regression (MLR)**.
Both **Excel** and **Python (Jupyter Notebook)** implementations are provided to validate the results.
The aim is to identify **significant variables** affecting financial health and test consistency across industries.

---

## 📂 Repository Structure
```
Financial_Health_Prediction_Project/
│
├── 1. Report/
│   └── Financial_Health_Prediction.docx (Main project report)
│
├── 2. Data & Excel Analysis/
│   └── Financial_Health_Prediction.xlsx (Data + Excel-based regression analysis)
│
├── 3. Python Implementation/
│   └── Pragya_Gupta_RBA55_Assignment_1.ipynb (Python EDA + MLR + diagnostics)
│
├── 4. Supporting Material/
│   ├── README.md (This file – project overview and usage guide)
│   ├── requirements.txt (Python dependencies)
│   └── [Optional] Export of Notebook as HTML/PDF
```

---

## ⚙️ How to Use

### 1. Report
- Open **Financial_Health_Prediction.docx** (or PDF version) to read the project methodology, analysis steps, and conclusions.

### 2. Excel Analysis
- Open **Financial_Health_Prediction.xlsx**
  - Sheets contain raw data, cleaned dataset, and regression outputs.
  - A "ReadMe" sheet is recommended inside Excel for clarity.

### 3. Python Notebook
- File: **Pragya_Gupta_RBA55_Assignment_1.ipynb**
- Steps:
  1. Install required packages (`requirements.txt`).
  2. Run each cell sequentially for data loading, cleaning, regression, and diagnostics.
  3. Results include significant variables, VIF check, and residual diagnostics.

---

## 🛠️ Requirements
- Python 3.8+
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - statsmodels
  - scikit-learn

Install dependencies:
```
pip install -r requirements.txt
```

---

## 📊 Key Deliverables
- **Significant variables** affecting financial health identified using p-values & VIF.
- **Stepwise regression** approach applied until only significant predictors remain.
- **Comparison across industries** to find consistently significant variables.
- **Model diagnostics** checked for linearity, multicollinearity, and homoscedasticity.

---

## ✍️ Author
- **Pragya Gupta**
- PGDM (Research & Business Analytics), WeSchool
