# Quick E-Commerce Analytics Dashboard 📊

## 📌 Project Overview
This project presents an interactive **Power BI dashboard** analyzing the performance of India’s **Quick E-Commerce platforms** such as Blinkit, Zepto, Swiggy Instamart, Amazon Now, Flipkart Minutes, Dunzo, JioMart, and BigBasket.

The dashboard provides actionable insights on **order value, delivery time, ratings, discounts, payment methods, cities, and product categories**.

---

## 🎯 Business Objectives
- Compare revenue contribution across quick commerce platforms  
- Analyze delivery efficiency vs distance  
- Understand customer & delivery partner ratings  
- Identify high-performing cities and categories  
- Evaluate impact of discounts and payment methods  

---

## 📊 Key KPIs
- **Total Order Value:** ₹541M  
- **Average Delivery Partner Rating:** 3.80  
- **Average Customer Rating:** 3.04  
- **Average Discount:** 0.40  
- **Delivery Time vs Distance (KM → Minutes)**  

---

## 📂 Dashboard Insights
- 🏪 **Platform-wise performance** (Blinkit, Zepto, Swiggy Instamart, etc.)
- 🥦 **Category analysis** (Groceries, Dairy, Snacks, Beverages, Fruits & Vegetables)
- 🌆 **City-level demand** (Delhi, Gurgaon, Noida, Mumbai, Bengaluru, etc.)
- 💳 **Payment mode distribution** (UPI, Credit Card, Debit Card, Wallet, COD)
- 🚚 **Delivery time increases linearly with distance**

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **SQL (Data Cleaning & Modeling)**
- **DAX Measures**
- **Excel / CSV Dataset**
- **Data Visualization & Business Analytics**

---

## 🧮 Key DAX Measures Used
```DAX
Total Order Value = SUM(Orders[Order_Value])

Average Customer Rating = AVERAGE(Orders[Customer_Rating])

Average Delivery Rating = AVERAGE(Orders[Delivery_Partner_Rating])

Average Discount = AVERAGE(Orders[Discount])
