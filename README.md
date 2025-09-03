# 📖 Customer Data Processing – README  

## 📌 Overview  
This project demonstrates how to take raw customer data from a CSV file and apply **Python-based data processing** to extract **business insights**. It focuses on **real-world scenarios** like customer segmentation, country distribution, company-level analysis, and data quality checks.  

---

## 🎯 Objectives  
- Practice **Python basics** (loops, functions, conditionals) in a **data engineering context**.  
- Understand how to transform **raw CSV data** into **business-friendly information**.  
- Reinforce concepts like **customer segmentation, validation, and pricing rules**.  

---

## 📂 Input Data (data.csv)  
The dataset contains customer-related fields such as:  

- **Customer Id** – Unique identifier  
- **First Name / Last Name** – Customer’s name  
- **Company** – Organization customer belongs to  
- **City / Country** – Location information  
- **Phone 1 / Phone 2** – Contact numbers  
- **Email** – Contact email  
- **Subscription Date** – Date customer subscribed  
- **Website** – Company/Customer website  

---

## 🔍 Business Logic Implemented  

1. **Customer Segmentation**  
   - Based on subscription year:  
     - `Loyal` → Joined before 2015  
     - `Regular` → Joined between 2015–2020  
     - `New` → Joined after 2020  

2. **Country Distribution**  
   - Count customers per country.  
   - Helps identify **strong vs weak markets**.  

3. **Top Companies by Customers**  
   - Rank companies by number of customers.  
   - Highlights **key corporate accounts**.  

4. **Data Quality Checks**  
   - Validate email & phone.  
   - Flag missing contacts → ensures **clean communication channels**.  

5. **Subscription Renewal Pricing**  
   - Apply discount rules:  
     - Loyal → 20% discount  
     - Regular → 10% discount  
     - New → No discount  
   - Supports **loyalty-based pricing strategy**.  

---

## 📈 Why This Matters  
- Transforms raw rows into **actionable insights**.  
- Helps **business teams** (marketing, sales, customer success).  
- Simulates **real-world data engineering use cases**.  

---

## ✅ Expected Output  
After running the script, you should be able to answer:  
- Who are my **loyal customers**?  
- Which **countries** have the most customers?  
- Which **companies** bring the highest customer volume?  
- Do we have **clean contact data**?  
- What is the **discount-adjusted renewal price**?  
