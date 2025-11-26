# 🛒 E-Commerce Order Fulfillment & Performance Analysis

## 📘 Project Overview
This project explores the **order fulfillment and sales performance** of an e-commerce business.  
It aims to uncover insights into **sales trends, customer behavior, product performance, shipping costs, and payment preferences** to improve decision-making and operational efficiency.

Using **Advanced SQL** and **Python (Pandas, Matplotlib, Seaborn)**, this analysis helps optimize logistics, boost sales, and enhance customer satisfaction.

---

## 🎯 Objectives
- Analyze **order processing efficiency** to reduce fulfillment delays.  
- Identify **top-performing products and categories** driving revenue.  
- Segment **high-value customers** based on purchase frequency and spend.  
- Evaluate **shipping costs** to improve logistics optimization.  
- Understand **payment preferences** to improve checkout conversions.

---

## 📂 Dataset Overview
- **Records:** 51,000+ rows, 16 columns  
- **Data Source:** Synthetic e-commerce transactions  
- **Tables:**
  - `Orders` – Order details (sales, profit, and shipping data)  
  - `Customers` – Customer demographics and behavior  
  - `Products` – Product-level details  
  - `Categories` – Product classifications  

Data was normalized into relational tables to enable efficient SQL querying and data integrity.

---

## ⚙️ Technical Approach

### 🔹 Advanced SQL Techniques
- **Window Functions:** Calculated running totals, rankings, and cumulative sales.
- **CTEs (Common Table Expressions):** Simplified segmentation and multi-step transformations.
- **Ranking & Aggregation:** Identified top products and customer cohorts.
- **Optimization:** Used indexing and partitioning for performance improvement.

### 🔹 Python Data Analysis
- Cleaned and transformed raw exports using **Pandas**.  
- Performed **EDA** (Exploratory Data Analysis) and visualization with **Matplotlib** and **Seaborn**.  
- Integrated SQL queries directly within **Jupyter Notebook** for hybrid SQL–Python workflows.

---

## 📊 Key Insights

### 💰 Sales & Revenue
- Total revenue: **~$7.8M**, with a **46% profit margin**.  
- **May and November** recorded the highest monthly sales.

### 👕 Product Performance
- **Fashion and Footwear** dominated sales; top SKUs were **T-shirts, Watches, and Running Shoes**.  
- Bundling slow movers with top sellers can improve conversion rates.

### 👨‍💼 Customer Behavior
- **High-value male customers** contributed most to repeat purchases.  
- Targeted loyalty campaigns can improve retention rates.

### 🚚 Order Fulfillment
- **High-priority shipments** incurred significantly higher costs.  
- Encouraging **standard delivery options** can reduce logistics spend.

### 💳 Payment Preferences
- **Credit cards** accounted for over **70% of total payments**.  
- Introducing **cashback on e-wallets and UPI** can increase adoption.

---

## 💡 Recommendations
- Implement **warehouse automation** and **real-time tracking** to reduce order delays.  
- Launch **seasonal offers** during peak sales months.  
- Introduce **loyalty rewards and personalized discounts** for frequent buyers.  
- Optimize carrier contracts for **bulk shipping discounts**.  
- Promote **digital payment incentives** to diversify transaction modes.

---

## 🧰 Technologies Used
| Category | Tools & Technologies |
|-----------|----------------------|
| Database | SQLite |
| Query Language | SQL |
| Programming | Python |
| Libraries | Pandas, Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## 📁 Repository Structure
