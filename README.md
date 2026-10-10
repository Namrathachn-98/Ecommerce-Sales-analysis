# 🛒 E-Commerce Sales Analysis

### Exploratory Data Analysis | Python | Pandas | Matplotlib | Seaborn

## 📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an online retail dataset to uncover meaningful insights into sales performance, customer purchasing behaviour, product demand, and geographical sales distribution.

Using Python and data visualization techniques, the project transforms raw transactional data into actionable business insights that can support data-driven decision-making.

## 🎯 Project Objectives

- Analyze monthly sales trends and identify high-performing periods.
- Identify top customers based on sales value.
- Examine repeat customer purchasing patterns.
- Compare sales performance across countries.
- Identify top-performing products by quantity sold and sales value.
- Clean and validate the dataset before analysis.
- Present findings through clear visualizations and business recommendations.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and processing |
| Pandas | Data cleaning, manipulation, and aggregation |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Google Colab | Notebook development and execution |
| Git & GitHub | Version control and project hosting |

## 📂 Project Structure

```text
Ecommerce-Sales-analysis/
│
├── Ecommerce_Sales_EDA.ipynb
├── README.md
└── dataset (if included)
```

The notebook contains the data preparation, exploratory analysis, visualizations, findings, and final conclusions. The dataset may need to be downloaded separately if it is not included in the repository.

## 📊 Dataset Information

The analysis uses an Online Retail transactional dataset containing information about invoices, products, quantities, transaction dates, unit prices, customer IDs, and countries.

**Dataset details after cleaning:**

- Original records: 541,909
- Cleaned records: 526,052
- Number of columns after cleaning and feature engineering: 9
- Transaction period: December 2010 – December 2011
- Engineered feature: `TotalSales`

The `TotalSales` column is calculated as:

`TotalSales = Quantity × UnitPrice`

## 🔍 Key Analyses & Findings

### 1. Monthly Sales Trend
Analyzed monthly sales values to identify periods of higher and lower sales activity. November 2011 recorded the highest monthly sales value in the cleaned dataset.

### 2. Top 10 Customers by Sales Value
Identified customers contributing the highest sales values. The top 10 customers together accounted for approximately **£1.54 million** in recorded sales value.

### 3. Repeat Customer Analysis
Among 4,339 customers with identifiable customer IDs, 2,845 had more than one distinct invoice, representing approximately **65.57%** of identifiable customers.

### 4. Country-Wise Sales Analysis
Compared sales values across countries. The United Kingdom contributed the largest sales value among the countries analyzed.

### 5. Product Performance by Quantity
Identified products with the highest quantities sold. *PAPER CRAFT, LITTLE BIRDIE* ranked first by quantity in the cleaned dataset.

### 6. Product Performance by Sales Value
Ranked products by recorded sales value. The analysis also highlighted the importance of distinguishing physical products from entries such as postage and manual adjustments when interpreting product performance.

## 💡 Business Insights & Recommendations

- Investigate seasonal and monthly sales patterns to improve inventory and sales planning.
- Develop customer retention campaigns for customers who have made only one recorded purchase.
- Explore international markets to identify potential growth opportunities.
- Evaluate products using both quantity sold and sales value.
- Improve customer identification and investigate missing product descriptions to strengthen future analysis.
- Separate merchandise sales from postage and adjustment entries for more meaningful product comparisons.

## 🧹 Data Cleaning & Validation

The cleaning and validation checks showed:

- No exact duplicate rows remained in the cleaned dataset.
- No negative quantities or negative unit prices remained.
- The `TotalSales` calculation was consistent with quantity multiplied by unit price within the validation tolerance.
- Some records still had missing `CustomerID` and `Description` values.

Approximately 25.3% of cleaned rows had missing customer IDs, which limits customer-level analysis.

**Important limitation:** Cancellation invoice rows and negative-quantity records were absent from the cleaned dataset. Therefore, the reported sales total should not be interpreted as verified net revenue after returns. The original dataset would need to be examined to quantify returns and cancellations accurately.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open `Ecommerce_Sales_EDA.ipynb` in Google Colab or Jupyter Notebook.
3. Upload or configure access to the required dataset.
4. Run the notebook cells in order, from top to bottom.
5. Review the visualizations, analytical results, and conclusions.

## 📈 Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data aggregation and grouping
- Feature engineering
- Customer and product analytics
- Time-series trend analysis
- Data visualization
- Business insight generation
- Data validation and interpretation
- GitHub project documentation

## 🏁 Conclusion

This project demonstrates how Python-based exploratory data analysis can reveal patterns in retail transactions and help explain sales trends, customer purchasing behaviour, product performance, and geographical distribution.

It showcases practical skills in data analysis, visualization, and business interpretation while highlighting the importance of data quality and analytical limitations.

---

**Author:** Namratha

**Project:** E-Commerce Sales Analysis

**Repository:** [Ecommerce-Sales-analysis](https://github.com/Namrathachn-98/Ecommerce-Sales-analysis)
