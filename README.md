# 📊 Amazon Sales Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on Amazon sales data to identify meaningful business insights related to sales performance, product categories, geographical markets, order fulfilment, cancellations, and monthly sales trends.

The objective of this project is to transform raw sales data into meaningful insights using Python-based data analysis and visualization techniques.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall sales performance.
- Identify the highest revenue-generating product categories.
- Analyze product quantity sold across different categories.
- Identify top-performing cities and states by revenue.
- Analyze order cancellation patterns.
- Compare Amazon and Merchant fulfilment.
- Analyze monthly revenue and quantity trends.
- Calculate and analyze Average Selling Price (ASP).
- Generate meaningful business insights from the data.

---

## 🛠️ Tools and Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

The dataset used in this project is publicly available on Kaggle.

**Dataset Source:** Kaggle  
**Dataset File Used:** `Amazon Sale Report.csv`

**Dataset Link:**  
[Amazon Sales Report Dataset on Kaggle](https://www.kaggle.com/datasets/arpit2712/amazonsalesreport)

> The dataset is not included in this repository. Please download it from the original Kaggle source before running the notebook.

---

## 📊 Key Areas of Analysis

### 1. Order Status Analysis

The overall order status distribution was analyzed to understand the proportion of shipped, cancelled, pending, and other order statuses.

### 2. Fulfilment Analysis

The performance of different fulfilment methods was analyzed to compare Amazon Fulfilment and Merchant Fulfilment.

### 3. Cancellation Analysis

Cancellation patterns were investigated to identify:

- Overall cancellation rate.
- Cancellation rate by fulfilment type.
- State-wise cancellation patterns.
- Relationship between cancellations and courier status.
- Missing financial information associated with cancelled orders.

### 4. Product Category Analysis

Product categories were analyzed based on:

- Revenue generated.
- Quantity sold.
- Average Selling Price (ASP).

### 5. Geographic Analysis

Geographical sales performance was analyzed to identify:

- Top revenue-generating states.
- Top revenue-generating cities.
- Major geographical markets contributing to sales.

### 6. Monthly Trend Analysis

Monthly trends were analyzed for:

- Revenue.
- Quantity sold.
- Average Selling Price (ASP).

Only comparable full-month periods were considered for monthly trend interpretation.

---

## 📈 Key Visualizations

The project includes the following visualizations:

### 1️⃣ Revenue by Product Category

Identifies the product categories generating the highest revenue.

### 2️⃣ Quantity Sold by Product Category

Shows the sales quantity distribution across product categories.

### 3️⃣ Top 10 Cities by Revenue

Identifies the strongest city-level markets.

### 4️⃣ Top 10 States by Revenue

Identifies the highest revenue-generating states.

### 5️⃣ Monthly Revenue Trend

Shows the revenue trend across comparable months.

### 6️⃣ Monthly Quantity Sold Trend

Shows changes in product quantity sold over time.

### 7️⃣ Average Selling Price by Product Category

Compares the average selling price across different product categories.

### 8️⃣ Monthly Average Selling Price Trend

Shows how the average selling price changes across comparable months.

---

## 🔍 Key Business Insights

Some important insights obtained from the analysis include:

- **Set** was the highest revenue-generating product category.
- **Kurta** was also one of the major contributors to revenue and sales quantity.
- Revenue was concentrated in a few major geographical markets.
- **Bengaluru, Hyderabad, Mumbai, Delhi, Chennai, and Pune** were among the leading cities by revenue.
- Major states contributed significantly to overall sales performance.
- A noticeable proportion of orders were cancelled, highlighting the importance of analysing cancellation behaviour.
- Merchant fulfilment showed a higher cancellation rate relative to the number of orders processed compared with Amazon fulfilment.
- Monthly revenue and quantity trends provided insights into changes in sales performance over time.
- Average Selling Price analysis showed differences in pricing across product categories.

---

## 📁 Project Structure
```text
Amazon-Sales-Data-Analysis/
│
├── Amazon_Sale_Analysis.ipynb
│
├── visualizations/
│   ├── 01_revenue_by_category.png
│   ├── 02_quantity_by_category.png
│   ├── 03_top_10_cities_revenue.png
│   ├── 04_top_10_states_revenue.png
│   ├── 05_monthly_revenue_trend.png
│   ├── 06_monthly_quantity_trend.png
│   ├── 07_average_selling_price_by_category.png
│   └── 08_monthly_asp_trend.png
│
├── Report/
│   └── Amazon_Sales_Analysis_Report.pdf
│
└── README.md


