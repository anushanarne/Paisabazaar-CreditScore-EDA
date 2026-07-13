# Paisabazaar-EDA
Exploratory Data Analysis (EDA) project to analyze customer financial data and identify the key factors influencing credit scores.
# 📊 Paisabazaar Credit Risk Analysis

## 📌 Project Overview

This project analyzes customer financial data to understand the key factors influencing credit scores and credit risk. Using Exploratory Data Analysis (EDA), the project uncovers patterns in customer financial behavior, identifies customer risk segments, and provides actionable insights that can help Paisabazaar improve lending decisions, reduce default risk, and enhance customer experience.

---

## 📝 Problem Statement

Paisabazaar faces the challenge of accurately evaluating customer creditworthiness. Customers exhibit diverse financial behaviors—some maintain healthy financial discipline, while others struggle with delayed payments, high debt, or excessive credit utilization.

Without a robust data-driven approach, it becomes difficult to:

- Identify high-risk customers early.
- Offer the right financial products to the right customer segments.
- Balance business growth with effective risk management.
- Minimize loan defaults while maintaining profitability.

---

## 🎯 Business Objective

The primary objectives of this project are to:

- Identify the key factors influencing customer credit scores.
- Analyze customer financial behavior and spending patterns.
- Segment customers into Good, Standard, and Poor credit risk categories.
- Detect high-risk customers before loan approval.
- Support data-driven lending decisions.
- Improve customer targeting and reduce loan default risk.

---

## 📂 Dataset

The dataset contains customer financial and credit-related information, including:

- Credit Score
- Payment Behavior
- Monthly Income
- Outstanding Debt
- EMI
- Credit Utilization Ratio
- Monthly Balance
- Credit History Age
- Number of Bank Accounts
- Number of Credit Cards
- Number of Loan Inquiries
- Other financial attributes

---

## ⚙️ Methodology

### Data Cleaning & Preparation
- Removed duplicate records.
- Handled missing values.
- Corrected inconsistent data formats.
- Converted data types where required.

### Feature Engineering
- Created meaningful financial metrics.
- Prepared the dataset for analysis.
- Encoded categorical variables where necessary.

### Outlier Handling
- Applied Winsorization by capping extreme values at the 1st and 99th percentiles.
- Reduced the influence of extreme values while preserving all observations.

### Exploratory Data Analysis (EDA)

Performed analysis using:

- Distribution Plots
- Histograms
- Box Plots
- Scatter Plots
- Count Plots
- Correlation Heatmaps
- Pair Plots

---

## 📈 Key Findings

- **Payment Behavior:** Customers who make timely payments consistently achieve higher credit scores.
- **Debt-to-Income Ratio:** Higher debt relative to income is strongly associated with lower credit scores.
- **EMI-to-Salary Ratio:** Customers with manageable EMI obligations demonstrate healthier financial profiles.
- **Credit Utilization:** Lower utilization reflects responsible credit management and contributes to better credit scores.
- **Monthly Balance:** Stable monthly balances indicate sound financial discipline.
- **Credit History Age:** Longer credit histories generally lead to stronger creditworthiness.
- **Loan Inquiries:** Frequent credit inquiries slightly reduce credit scores, indicating higher financial risk.

---

## 👥 Customer Segmentation

### 🟢 Good Credit Score
- Financially disciplined customers.
- Low lending risk.
- Suitable for premium financial products.

### 🟡 Standard Credit Score
- Moderate financial risk.
- Opportunity for improvement through responsible credit behavior.

### 🔴 Poor Credit Score
- High repayment risk.
- Delayed payments, excessive debt, and high credit utilization.
- Requires closer monitoring and financial guidance.

---

## 💼 Business Insights

### Benefits

- Improve credit risk assessment.
- Personalize financial product recommendations.
- Identify high-value customers.
- Support fair and data-driven lending decisions.
- Strengthen customer retention and loyalty.

### Business Risks

- Increased loan defaults due to high debt burdens.
- Inefficient customer targeting.
- Higher financial exposure from excessive borrowing and frequent credit inquiries.

---

## 🚀 Business Solution

Based on the insights obtained from EDA, Paisabazaar can:

- Build predictive credit scoring models using financial and behavioral indicators.
- Segment customers into Low, Medium, and High-risk groups.
- Offer premium products and better interest rates to financially disciplined customers.
- Provide financial counseling or loan restructuring options for high-risk customers.
- Continuously monitor customer behavior and update credit risk models to improve prediction accuracy.

---

## 💡 Recommendations

- Enhance credit scoring models using behavioral and financial ratio-based features.
- Promote responsible borrowing through personalized financial guidance.
- Develop targeted financial products for different customer segments.
- Continuously refine lending policies using updated customer data.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

---

## 📁 Project Structure

```text
Paisabazaar-Credit-Risk-Analysis/
│
├── Paisabazaar_Credit_Risk_Analysis.ipynb
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Install the required libraries.
4. Run all cells sequentially.

---

## 📌 Conclusion

This project demonstrates that customer financial behavior has a significant impact on credit scores and overall credit risk. Timely payments, balanced debt levels, responsible credit utilization, and stable financial habits are key indicators of creditworthiness. The insights generated through EDA enable Paisabazaar to improve risk assessment, personalize financial products, reduce loan defaults, and support sustainable business growth through data-driven decision-making.
