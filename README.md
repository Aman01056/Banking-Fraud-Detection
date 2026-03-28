# Banking Fraud Detection using SQL

## 📌 Objective

Analyze banking transactions to detect fraudulent or suspicious activities using SQL.

## 🛠 Tools Used

* SQL (MySQL)

## 📊 Dataset

Contains transaction-level data including:

* Customer ID
* Transaction Amount
* Transaction Type
* Date & Time
* Location

## 🔍 Key Analysis Performed

* Identified high-value transactions (>50,000)
* Detected rapid transactions using window functions (LAG)
* Analyzed location changes for suspicious activity
* Created fraud scoring model using CASE WHEN

## 💡 Key Insights

* Customers performing multiple transactions within minutes are high-risk
* High-value and international transactions increase fraud probability
* Sudden location changes indicate suspicious behavior

## 🚀 Conclusion

SQL can be effectively used to detect fraud patterns and analyze risk in financial datasets.

## 📁 Project Structure

* dataset.csv
* queries.sql
* README.md
