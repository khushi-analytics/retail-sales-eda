# 📊 Exploratory Data Analysis on Sales Data

This project explores a sample retail sales dataset and uncovers trends, patterns, and insights through data cleaning, aggregation, and visual storytelling.

---

## 📁 Dataset

- **Source**: [Kaggle](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
- **Size**: 2,823 rows × 25 columns
- **Fields** include: `ORDERDATE`, `SALES`, `PRODUCTLINE`, `DEALSIZE`, `STATUS`, `COUNTRY`, etc.

---

## 🧰 Tools & Libraries

- Python 🐍
- pandas for data manipulation
- seaborn & matplotlib for visualizations
- Google Colab for notebook execution

---

## 🔎 Key Analyses & Visuals

### 1. 📅 Sales Trends Over Time
- Created new columns for `MONTH` and `YEAR` from the `ORDERDATE`.
- Visualized **monthly and yearly revenue trends** using line plots.
- Identified seasonal sales peaks and business growth patterns.

### 2. 📦 Product Line Performance
- Compared total revenue across all `PRODUCTLINE` categories.
- Found **Classic Cars** and **Vintage Cars** consistently outperform other lines.
- Used bar plots and aggregation for comparative insights.

### 3. 🛍 Deal Size & Sales Distribution
- Analyzed how `DEALSIZE` affects revenue.
- Larger deal sizes led to **higher but more variable** sales — a valuable insight for pricing and inventory strategy.

### 4. 📌 Categorical Feature Utility
- Found `STATUS` and `PRODUCTLINE` to be **strong predictors** of revenue patterns.
- Cleaned and prepared these for possible use in future ML models.

---

## 📈 Key Insights

- Sales peaked in **2004**, with monthly patterns indicating **seasonality**.
- Product categories are **not equally profitable** — focus can be placed on high-value segments.
- Deal size significantly affects **sales volatility**.
- Certain categorical variables show clear structure in the data, useful for modeling.

---

## 🔗 Notebook
👉 [View in Colab](https://github.com/khushi-analytics/retail-sales-eda/blob/main/Retail_sales_EDA.ipynb)
