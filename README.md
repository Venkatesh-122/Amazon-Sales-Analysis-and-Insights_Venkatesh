---

## 🛒 Amazon Sales Data Analysis

### 📘 Project Overview

This project performs an **end-to-end analysis of Amazon Sales Transactions**, uncovering key insights into sales trends, product performance, fulfillment efficiency, customer segmentation, and geographical distribution.
The dataset provides details about orders, sales channels, fulfillment types, and locations, enabling data-driven business recommendations.

---

### 🎯 Objectives

The primary goals of this analysis are to:

1. **Sales Overview** – Understand sales performance, trends, and seasonality.
2. **Product Analysis** – Identify top-performing categories and products.
3. **Fulfillment Analysis** – Compare fulfillment methods and their impact on delivery efficiency.
4. **Customer Segmentation** – Segment customers based on buying behavior and location.
5. **Geographical Analysis** – Analyze sales distribution across states and cities.
6. **Business Insights & Recommendations** – Provide actionable insights to optimize operations.

---

### 🧾 Dataset Information

| Column Name      | Description                                   |
| ---------------- | --------------------------------------------- |
| Order ID         | Unique order identifier                       |
| Date             | Order date                                    |
| Status           | Order status (Shipped, Cancelled, etc.)       |
| Fulfilment       | Fulfillment type (Amazon / Merchant)          |
| Sales Channel    | Source of sale (Online, App, etc.)            |
| Category         | Product category                              |
| Qty              | Quantity sold                                 |
| Amount           | Sale amount (₹)                               |
| ship-city        | Customer’s city                               |
| ship-state       | Customer’s state                              |
| ship-country     | Country                                       |
| ship-postal-code | Pincode                                       |
| fulfilled-by     | Seller/Fulfillment agent                      |
| Courier Status   | Delivery status (Delivered, In Transit, etc.) |

---

### 🧹 Data Cleaning Steps

1. **Handled Missing Values** – Identified and visualized missing data using Seaborn & Matplotlib.
2. **Removed Null Records** – Dropped rows with missing `Amount`, `Rating`, and `ReleaseDate`.
3. **Formatted Columns** – Converted data types and standardized column names.
4. **Verified Data Quality** – Ensured consistency across numeric and categorical attributes.

---

### 📊 Exploratory Data Analysis (EDA)

Key analysis steps and their visualizations:

| Step                         | Description                                      | Visualizations        |
| ---------------------------- | ------------------------------------------------ | --------------------- |
| **1. Sales Overview**        | Trend of sales over time                         | Line/Bar plots        |
| **2. Product Analysis**      | Top categories and quantity distribution         | Bar charts            |
| **3. Fulfillment Analysis**  | Amazon vs Merchant performance                   | Count & Pie plots     |
| **4. Customer Segmentation** | Segment based on location and purchase frequency | Seaborn barplots      |
| **5. Geographical Analysis** | Top 10 states and cities by sales                | Horizontal bar charts |
| **6. Business Insights**     | Summary metrics & recommendations                | Text-based report     |

---

### 💡 Business Insights & Recommendations

| Focus Area        | Recommendation                                                                               |
| ----------------- | -------------------------------------------------------------------------------------------- |
| Product Strategy  | Focus marketing on top categories like *T-shirts* and *Shirts*.                              |
| Logistics         | Improve merchant fulfillment efficiency; scale Amazon Fulfillment during high-volume months. |
| Marketing         | Target high-spending cities (Bengaluru, Hyderabad) with exclusive campaigns.                 |
| Operations        | Introduce bundle offers for mid-tier categories (Blazers, Trousers).                         |
| Seasonal Planning | Leverage off-season discounts during July–December to boost sales.                           |

---

### 📈 Tools & Libraries Used

| Category              | Libraries                       |
| --------------------- | ------------------------------- |
| **Data Manipulation** | `pandas`, `numpy`               |
| **Visualization**     | `matplotlib`, `seaborn`         |
| **Environment**       | Jupyter Notebook / Google Colab |
| **Version Control**   | Git, GitHub                     |

---

### 📂 Repository Structure

```
📦 Amazon-Sales-Analysis
│
├── 📄 Amazon_Sales_Analysis.ipynb       # Main analysis notebook
├── 📄 Amazon_Sales_Report.csv            # Dataset
├── 📄 README.md                          # Project overview and documentation
└── 📁 images/                            # (Optional) Exported graphs & charts
```

---

### 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/<your-username>/Amazon-Sales-Analysis.git
   cd Amazon-Sales-Analysis
   ```
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open the notebook:

   ```bash
   jupyter notebook Amazon_Sales_Analysis.ipynb
   ```
4. Run all cells to view the analysis and visualizations.

---

### 🧠 Key Takeaways

* Maharashtra and Karnataka are top revenue-generating states.
* Amazon Fulfillment outperforms Merchant Fulfillment in reliability.
* Apparel categories (T-shirts, Shirts) dominate total sales.
* High-spending cities include Bengaluru and Hyderabad.
* Around 70% missing values found in `fulfilled-by` column — requires data quality improvement.

---

### ✍️ Author

**M. Venkatesh**
📧 Email: venkateshvenkateah789@gmail.com

---


1. **Add Markdown formatting (headings + icons)** for better GitHub readability, or
2. **Keep it minimal (plain README.md text)** suitable for a professional submission report?
