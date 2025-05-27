# STATISTIC-ANALYSIS
# 🛍️ E-Commerce Transaction Statistical Analysis

This project presents a complete end-to-end statistical analysis of a real-world e-commerce dataset. It combines descriptive and inferential statistics with exploratory data analysis (EDA) to derive actionable business insights from transactional data.

---

## 📊 Project Objective

The primary goals of this project are:

- To investigate whether **customer type** (Guest vs Returning) affects total spending.
- To assess if **revenue patterns** differ across **weekdays** or **hours**.
- To evaluate whether there is a **relationship between product price and quantity purchased**.
- To identify **top-performing products** and **revenue-contributing countries**.
- To demonstrate how basic statistics can guide real-world **business strategies**.

---

## 🧩 Dataset Overview

- **Source**: Simulated real-world retail data based on public e-commerce datasets.
- **Size**: 3,000+ transactions with attributes like:
  - `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`, and computed fields like `TotalPrice`, `InvoiceTotal`, `CustomerType`, `day_of_week`, and `hour`.

---

## 🧪 Statistical Methods Used

| Method            | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| Descriptive Stats| Summarize sales behavior (mean, std. dev, distributions)                |
| Independent T-Test| Compare spending between Guest vs Returning customers                   |
| One-Way ANOVA    | Test revenue differences across weekdays                                 |
| Pearson Correlation| Analyze price-quantity relationship                                     |

All computations were done using **Python (Pandas, SciPy, Seaborn, Matplotlib)**.

---

## 📈 Key Findings

- No significant difference in **Invoice Totals** between Guests and Returning customers *(p = 0.2199)*.
- No significant revenue variation across **weekdays** *(p = 0.2102)*.
- Weak and statistically insignificant correlation between **Unit Price** and **Quantity** *(corr = 0.03)*.
- Top 5 products account for **73% of revenue**:
  - Phone Case, Backpack, Charger, Pen, and T-Shirt.
- Balanced **revenue contribution from top countries**, including Italy, Australia, Netherlands, USA, and UK.
- **Average invoice value**: \$259.62.
- No free items or zero-value orders were detected in the dataset.

---

## 📌 Visualizations

Visual insights were generated for:

- 📦 Invoice Totals by Customer Type (Boxplot)
- 🕒 Sales by Hour and Weekday (Bar Charts)
- 💰 Quantity vs Unit Price (Scatter + Regression)
- 🌍 Revenue by Country and Product (Bar Charts)

All visualizations are available in the [notebook](./ECOMMERCESTATISTICALANALYSIS.ipynb).

---

## 🧠 Business Implications

- **Customer segmentation** by type may not be necessary.
- **Uniform staffing** is feasible across weekdays and hours.
- **Focus on high-revenue SKUs** for promotions and stock optimization.
- **International market strategy** can be balanced, as sales are not overly skewed to one country.

---

## 🛠️ Technologies Used

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- SciPy
- Jupyter Notebook

---

## 📂 Repository Structure

