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

![Q1](Screenshot:q1_High_value.png)
![Q2](<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/96a497f9-f174-4bbd-b820-59f210d8db28" />
)
![Q3](<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/ee4737e8-bff3-4f7f-882c-d7c9de6acfbc" />
)
![Q4](<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/a4ad6052-787f-4806-8be6-a350f2221286" />
)
![Q5](<img width="900" height="400" alt="image" src="https://github.com/user-attachments/assets/c71edc54-be9e-4b2e-a869-97217874c6f5" />
)

---

## 📁 Project Structure
