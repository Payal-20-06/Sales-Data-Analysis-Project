# 📊 Sales Data Dashboard & Analytics Project

## 🚀 Project Overview

This project focuses on analyzing sales performance using **Python, SQL, and Power BI** to generate meaningful business insights.

It demonstrates a complete data workflow — from raw data processing to interactive dashboard visualization.

---

## 🎯 Objective

To analyze sales data and identify trends, patterns, and key insights that help in data-driven decision-making.

---

## 🔄 Project Workflow

```
Raw Data → Data Cleaning (Python) → Statistical Analysis → SQL Queries → Dashboard (Power BI) → Insights
```

---

## 🛠️ Tools & Technologies

* **Python** (Pandas, NumPy)
* **Matplotlib & Seaborn** (Visualization)
* **Plotly** (Interactive Charts)
* **SQL** (Data Querying)
* **Power BI** (Dashboard)
* **GitHub** (Version Control)

---

## 📂 Dataset Description

The dataset contains:

* `order_year` → Year of order
* `order_month` → Month of order
* `total_revenue` → Revenue generated
* `total_orders` → Number of orders

---

## 🔍 Data Processing

* Cleaned dataset using Pandas
* Converted data types
* Removed missing values
* Created new feature:

  * **Revenue per Order**

---

## 📊 Statistical Analysis

* Mean, Median, Standard Deviation of revenue
* Correlation between orders and revenue
* Identified data trends and variability

---

## 🗄️ SQL Analysis

```sql
-- Total Revenue
SELECT SUM(total_revenue) FROM sales;

-- Revenue by Year
SELECT order_year, SUM(total_revenue)
FROM sales
GROUP BY order_year;

-- Monthly Revenue
SELECT order_month, SUM(total_revenue)
FROM sales
GROUP BY order_month
ORDER BY SUM(total_revenue) DESC;
```

---

## 📈 Python Visualization

```python
import plotly.express as px

fig = px.line(df, x="order_month", y="total_revenue",
              title="Monthly Revenue Trend")
fig.show()
```

---

## 📊 Power BI Dashboard Features

### 🔹 KPI Cards

* Total Revenue
* Total Orders
* Revenue per Order

### 🔹 Visualizations

* Bar Chart → Yearly Revenue
* Line Chart → Monthly Trends
* Scatter Plot → Orders vs Revenue

### 🔹 Interactive Features

* Slicers (Month & Year)
* Dynamic filtering
* Clean UI design

---

## 📷 Dashboard Preview

*C:\Users\Payal\OneDrive\Documents\GitHub\Sales-Data-Analysis-Project\image.png*

---

## 💡 Key Insights

* Revenue varies significantly across months
* Peak sales observed in specific months
* Strong correlation between orders and revenue
* Identified high and low performance periods

---

## 🧠 Learnings

* End-to-end data analysis workflow
* Data visualization and storytelling
* Dashboard design principles
* SQL and statistical analysis integration

---

## 📌 Future Improvements

* Add region-wise analysis
* Implement real-time data updates
* Enhance dashboard interactivity
* Deploy dashboard online

---

## 📁 Project Structure

```
Sales-Data-Analysis/
│── Project2.ipynb
│── cleaned_sales_data.csv
│── dashboard.pbix
│── README.md
```

---

## 🤝 Contribution

Feel free to fork this repository and enhance the project.

---

## ⭐ Acknowledgment

This project was developed as part of my learning journey in **Data Science and Analytics**.

---
