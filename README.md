# Paisabazaar-EDA
Exploratory Data Analysis (EDA) project to analyze customer financial data and identify the key factors influencing credit scores.
# 📊 Paisabazaar Credit Risk Analysis

## 📌 Project Overview

This project analyzes customer financial data to identify the key factors influencing credit scores and credit risk. Using Exploratory Data Analysis (EDA), the project uncovers financial behavior patterns that can help improve credit risk assessment, support informed lending decisions, and minimize default risk.

---

## 🎯 Project Objective

The primary objectives of this project are to:

* Identify the key drivers of customer credit scores.
* Analyze customer financial behavior.
* Support data-driven lending decisions.
* Reduce the risk of loan defaults.

---

## 📂 Dataset

The dataset contains customer financial and credit-related information, including:

* Credit Score
* Payment Behavior
* Monthly Income
* Outstanding Debt
* EMI
* Credit Utilization Ratio
* Monthly Balance
* Credit History Age
* Number of Bank Accounts
* Number of Credit Cards
* Number of Loan Inquiries
* Other financial attributes

---

## ⚙️ Project Workflow

### 1. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Corrected inconsistent data formats.
* Converted data types where required.

### 2. Feature Engineering

* Created meaningful financial metrics.
* Prepared the dataset for analysis.
* Encoded categorical variables where necessary.

### 3. Outlier Handling

* Applied Winsorization by capping extreme values at the 1st and 99th percentiles.
* Reduced the influence of unusually high and low values while retaining all observations.

### 4. Exploratory Data Analysis (EDA)

Performed analysis using:

* Distribution Plots
* Histograms
* Box Plots
* Scatter Plots
* Count Plots
* Correlation Heatmaps
* Pair Plots

---

## 📈 Key Findings

### ✔️ Payment Behavior

Customers who make timely payments generally have higher credit scores, while delayed payments are associated with lower scores.

### ✔️ Debt-to-Income Ratio

Higher debt relative to income increases financial stress and is associated with poorer credit scores.

### ✔️ EMI-to-Salary Ratio

Customers with manageable EMI commitments tend to maintain healthier credit profiles.

### ✔️ Credit Utilization

Lower credit utilization reflects responsible credit usage and contributes to better credit scores.

### ✔️ Monthly Balance

Customers maintaining stable monthly balances demonstrate better financial discipline.

### ✔️ Credit History Age

Longer and healthier credit histories generally contribute to improved credit scores.

---

## 👥 Customer Segmentation

### 🟢 Good Credit Score

* Financially disciplined customers.
* Ideal candidates for premium financial products.
* Low lending risk.

### 🟡 Standard Credit Score

* Moderate financial risk.
* Opportunity for financial improvement through responsible credit usage.

### 🔴 Poor Credit Score

* Higher repayment risk.
* Characterized by delayed payments, high debt, and excessive credit utilization.
* Requires closer monitoring and targeted financial support.

---

## 💼 Business Insights

### Positive Impact

* Improve credit risk assessment.
* Personalize financial product recommendations.
* Identify high-value customers.
* Support fair and data-driven lending decisions.
* Strengthen customer retention and loyalty.

### Potential Business Risks

* Increased loan defaults due to high debt burdens.
* Inefficient customer targeting if key financial indicators are overlooked.
* Rising financial risk from excessive borrowing and frequent credit inquiries.

---

## 💡 Recommendations

* Enhance credit scoring models using behavioral and financial ratio-based features.
* Offer personalized financial products for different customer segments.
* Promote financial literacy and responsible borrowing.
* Continuously monitor customer behavior and refine lending policies.

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab
* Jupyter Notebook

---

## 📁 Project Structure

```text
Paisabazaar-Credit-Risk-Analysis/
│
├── Paisabazaar_Credit_Risk_Analysis.ipynb
├── README.md
├── dataset.csv (optional)
├── images/ (optional)
└── requirements.txt (optional)
```

---

## 🚀 How to Run the Project

1. Clone the repository.
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Run all cells sequentially to reproduce the analysis.

---

## 📌 Conclusion

This project demonstrates how customer financial behavior directly influences credit scores and overall credit risk. The insights generated can help financial institutions make smarter lending decisions, personalize financial products, reduce default risk, and improve customer financial well-being through data-driven strategies.
