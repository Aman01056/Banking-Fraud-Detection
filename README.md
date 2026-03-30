# 💳 Banking Fraud Detection using SQL

## 📌 Objective
Analyze banking transactions to identify fraudulent or suspicious activities using SQL queries.

---

## 🛠️ Tools Used
- SQL (MySQL)

---

## 📊 Dataset
The dataset contains transaction-level data including:
- Customer ID
- Transaction Amount
- Transaction Date
- Transaction Type
- Location

---

## 🔍 Key Analysis Performed

### 1. High Value Transactions
- Identified transactions greater than ₹50,000

### 2. Multiple Transactions in Same Day
- Detected customers performing multiple transactions in a single day

### 3. Previous Transaction Analysis (LAG)
- Used window function to track previous transactions

### 4. Rapid Transactions Detection
- Flagged transactions occurring within short time intervals (<5 minutes)

### 5. Fraud Score Calculation
- Assigned fraud scores based on suspicious behavior

---

## 📸 Screenshots

![Q1]("C:\Users\shaky\OneDrive\cv\Desktop\q1_High_value.png")
![Q2](Screenshot:q2_Multiple_Txn.png)
![Q3](Screenshot:q3_Lag.png)
![Q4](Screenshot:q4_Rapid.png)
![Q5](Screenshot:q5_Fraud_Score.png)

---

## 📁 Project Structure
