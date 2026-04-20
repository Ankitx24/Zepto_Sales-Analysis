# 🛒 Zepto Sales Data Analysis

A Python-based exploratory data analysis (EDA) project that dives into Zepto's sales and product data to uncover key business insights — from top-performing products to city-wise revenue and delivery performance.

---

## 📌 Project Overview

This project performs end-to-end data analysis on two datasets — **sales** and **products** — from Zepto, a quick-commerce grocery platform. It covers data cleaning, aggregation, grouping, merging, and rich visualizations to answer real business questions.

---

## 📂 Datasets Used

| File | Description |
|------|-------------|
| `zepto_sales.csv` | Order-level sales data including city, delivery time, order date, and total amount |
| `zepto_products.csv` | Product catalog with product IDs, names, and categories |

---

## 🔧 Tech Stack

- **Python 3.x**
- **Pandas** – Data manipulation and aggregation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical plotting

---

## 📊 Analysis Performed

### 🔍 Exploratory Data Analysis
- Dataset shape, column names, data types
- Summary statistics (`.describe()`)
- First and last few rows preview

### 🧹 Data Cleaning
- Dropped rows with missing values in `city` and `delivery_status`
- Filled missing `delivery_time_mins` values with column mean
- Removed duplicate records
- Converted `order_date` to proper `datetime` format

### 📈 Data Analysis & Aggregations
- Minimum, maximum, and average order amount
- **Top 5 products** by total sales amount (merged with product names)
- **Total sales by city**
- **Average delivery time by city**
- **Monthly sales trend** over time
- **Sales by product category**

---

## 📉 Visualizations

| Chart | Description |
|-------|-------------|
| 📊 Bar Chart | Top 5 products by sales amount |
| 📊 Bar Chart | Total sales by city |
| 📈 Line Chart | Monthly sales trend |
| 🥧 Pie Chart | Sales distribution by product category |
| 📉 Histogram + KDE | Distribution of delivery times |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/zepto-sales-analysis.git
cd zepto-sales-analysis
```

### 2. Install dependencies
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Add the datasets
Place `zepto_sales.csv` and `zepto_products.csv` in the project root directory.

### 4. Run the notebook
```bash
jupyter notebook Final_PythonProject.ipynb
```

---

## 📁 Project Structure

```
zepto-sales-analysis/
│
├── Final_PythonProject.ipynb   # Main analysis notebook
├── zepto_sales.csv             # Sales dataset
├── zepto_products.csv          # Products dataset
└── README.md                   # Project documentation
```

---

## 💡 Key Insights

- Identifies which products and cities drive the most revenue
- Reveals seasonal or monthly sales trends
- Highlights delivery time patterns across cities
- Shows which product categories are most popular by sales share

---

## 🙌 Acknowledgements

This project was built as part of a Python data analysis learning exercise, using a simulated Zepto-style dataset to practise real-world EDA workflows.
