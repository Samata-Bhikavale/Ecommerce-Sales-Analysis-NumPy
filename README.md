# Ecommerce-Sales-Analysis-NumPy
This project analyzes e-commerce sales data using NumPy, covering revenue, discounts, and customer insights
🛒 E-Commerce Sales Analysis with NumPy


🔹 **Objective**: Analyze key sales insights using **only NumPy (no pandas!)**  
🔹 **Dataset**: Randomly generated e-commerce transactions for 100 customers  
🔹 **Technologies Used**: NumPy, Jupyter Notebook, Python  

---

## 🗂️ Dataset Description  
The dataset consists of **100 e-commerce sales records** with the following fields:  

| Column Name         | Description                                  |
|---------------------|----------------------------------------------|
| `customer_ids`      | Unique ID for each customer                 |
| `product_categories`| Category of product (Electronics, Clothing, etc.) |
| `product_prices`    | Price of the product before discount        |
| `discounts`        | Discount percentage applied (0% to 30%)     |
| `quantities`       | Number of items purchased                   |
| `total_purchases`  | Final purchase value after discount         |
| `orders_per_month` | Number of orders placed by the customer per month |

---

## 📊 Key Insights & Analysis  

The project answers **10 key business questions** using NumPy:  

1️⃣ **Total revenue generated**  
2️⃣ **Average order value per customer**  
3️⃣ **Customer who received the highest discount**  
4️⃣ **Most purchased product category**  
5️⃣ **Category with the highest revenue**  
6️⃣ **Customer with the most purchases**  
7️⃣ **Customer with the highest total spending**  
8️⃣ **Top 5 highest revenue-generating transactions**  
9️⃣ **Effect of discounts on total revenue**  
🔟 **Average quantity of products per order**  

✅ **Techniques used**:  
- **NumPy indexing & slicing**  
- **Aggregation functions (`np.sum`, `np.mean`, `np.argmax`, etc.)**  
- **Sorting and filtering data**  

---

## 📂 Files in This Repository  

📌 **`ecommerce_sales_analysis.ipynb`** → Jupyter Notebook with full analysis  
📌 **`README.md`** → This document explaining the project  

---
2️⃣ Open the Jupyter Notebook
jupyter notebook
Open ecommerce_sales_analysis.ipynb

Run the cells step by step to analyze the dataset

🏆 Future Improvements
📌 Convert NumPy arrays to Pandas DataFrames for better data manipulation
📌 Use Matplotlib/Seaborn for data visualizations
📌 Expand dataset to include customer demographics
📌 Implement SQL queries for advanced analytics

🤝 Connect with Me
💡 If you found this project useful, give it a ⭐ on GitHub!
📩 Feel free to connect on LinkedIn-www.linkedin.com/in/samatabhikavale
### ✅ **Next Steps**
1️⃣ **Copy this `README.md`**  
2️⃣ **Paste it into GitHub** (edit LinkedIn & Medium links)  
3️⃣ **Upload your Jupyter Notebook**

## 🔧 How to Run  

### **1️⃣ Install Requirements**  
You only need NumPy and Jupyter Notebook:  
```bash
pip install numpy jupyter
