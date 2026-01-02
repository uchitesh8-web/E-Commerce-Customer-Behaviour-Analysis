# E-Commerce Customer Behaviour Analysis

## 📌 Project Overview

This project analyzes **e-commerce transactional data** to understand **customer behavior, sales trends, profitability, and operational efficiency**.
Raw e-commerce data is cleaned and standardized using **Python**, then visualized using **Power BI** to create an interactive, executive-level business dashboard.

The objective is to transform large-scale transaction data into **actionable insights** that support **revenue growth, customer retention, and logistics optimization**.

---

## 🎯 Business Objectives

* Measure overall sales, profit, and order volume
* Analyze customer segments and purchasing behavior
* Identify top-performing product categories
* Evaluate delivery performance across shipping modes
* Detect seasonal sales trends and high-value customers
* Enable self-service business analysis through dashboards

---

## 📂 Dataset Description

* Each row represents a single customer order from an e-commerce platform
* Dataset spans multiple years, enabling trend and behavior analysis

### Key Attributes:

* Order Date & Ship Date
* Customer ID & Segment
* Region & Country
* Product Category
* Sales, Profit, Quantity, Discount
* Shipping Cost & Shipping Mode

---

## 🛠 Tools & Technologies Used

* **Python (Pandas, NumPy)** – Data cleaning & preprocessing
* **Power BI** – Dashboard creation & business analytics

---

## 🧹 Data Preprocessing (Python)

Python was used to convert raw, inconsistent data into a reliable analytics-ready dataset:

### Key Steps:

* Loaded raw CSV data using Pandas
* Standardized date and currency formats for Power BI compatibility
* Cleaned financial columns (Sales, Profit, Shipping Cost):

  * Removed currency symbols and commas
  * Converted text to numeric values
  * Handled missing and invalid values safely
* Corrected categorical errors:

  * Fixed regional typos (e.g., “4orth” → “North”, “so3th” → “South”)
  * Removed non-business noise from Shipping Mode
* Converted Quantity and Discount into proper numeric formats
* Created new calculated metrics:

  * **Delivery Days** (Ship Date − Order Date)
* Replaced missing categorical values with `"Unknown"`
* Exported the cleaned dataset for Power BI analysis 

---

## 📊 Key Performance Indicators (KPIs)

* **Total Sales:** ₹8M
* **Total Profit:** ₹3.73M
* **Total Orders:** 51K

These KPIs provide an instant overview of business scale and performance .

---

## 🔍 Key Analysis & Insights

### 🚚 Operational Efficiency (Delivery Days)

* Same-Day shipping achieves near-zero delivery time
* First Class and Standard shipping average ~5.5 days
* Highlights opportunities to optimize standard shipping timelines 

---

### 📈 Sales Trends & Seasonality

* Strong sales surge observed in **March**
* Dip in sales during **February**
* Helps plan inventory and warehouse staffing proactively 

---

### 💰 Profit by Product Category

* **Fashion** is the top profit contributor (~₹2.5M)
* Electronics and Auto & Accessories generate significantly lower profit
* Identifies Fashion as the primary growth driver 

---

### 👥 Customer Segment Analysis

* Consumers account for **51% of total sales**
* Confirms the business is primarily **B2C-driven**
* Corporate and Home Office segments form smaller shares 

---

### ⭐ Top Customers (VIP Analysis)

* Identified Top 10 highest-value customers
* Individual customer spend reaches ~₹20K
* Enables targeted loyalty and retention strategies 

---

### 🌍 Global Sales Distribution

* Sales recorded across **38+ countries**
* Bubble map highlights high-revenue markets
* Supports regional expansion and market prioritization decisions 

---

## 🎛 Interactive Dashboard Features

The Power BI dashboard includes slicers for:

* Region
* Year / Quarter / Month

These controls allow stakeholders to perform **self-service analysis** and instantly answer business questions without manual reporting .

---

## 📈 Strategic Recommendations

* Reallocate marketing budget toward **Fashion category**
* Prepare inventory and staffing ahead of seasonal sales peaks
* Launch loyalty programs for high-value customers
* Optimize standard shipping timelines to improve customer satisfaction
* Use regional performance insights to guide expansion strategy 

---

## ✅ Conclusion

This project demonstrates how **Python-based data preprocessing** and **Power BI dashboards** can transform raw e-commerce transactions into a **decision-support system**.
It shifts analysis from static reporting to **proactive, insight-driven business strategy**.

---

## 📚 Learning Outcomes

* Large-scale data cleaning using Python
* Business-oriented KPI design
* Customer and sales behavior analysis
* Dashboard-driven storytelling for stakeholders

