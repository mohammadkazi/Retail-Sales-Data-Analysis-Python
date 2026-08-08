# Retail Sales Data Analysis — Python

An end-to-end retail sales analytics project using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The project covers **data loading, data-quality checks, cleaning, exploratory data analysis (EDA), KPI analysis, sales/profit trends, discount impact, customer segments, shipping performance, business insights, and automated visual exports**.

> **Important:** The notebook is designed to run immediately. If `data/retail_sales.csv` is not present, it creates a clearly labelled demo retail dataset so the workflow can still be tested. Replace it with your actual retail dataset for portfolio use.

## Business Questions

1. What are the overall sales, profit, orders, and average order value?
2. Which categories and sub-categories perform best?
3. Which regions and states generate the most sales and profit?
4. How do sales and profit change over time?
5. Does higher discounting reduce profitability?
6. Which customer segment contributes most to sales?
7. Which shipping modes are used most and which take longer?
8. Which products/categories need management attention?
9. Which business areas offer opportunities for improvement?

## Project Workflow

**Raw Data → Data Quality → Cleaning → Feature Engineering → EDA → KPI Analysis → Business Insights → Visual Exports**

## Key Analysis Areas

- Dataset shape and schema
- Missing-value analysis
- Duplicate detection
- Date conversion
- Shipping days
- Profit margin
- Average order value
- Category performance
- Sub-category performance
- Regional performance
- State-level performance
- Monthly and yearly trends
- Segment contribution
- Discount vs. profit
- Shipping-mode analysis
- Top and bottom performers
- Correlation analysis
- Automated business recommendations

## Repository Structure

```text
Retail-Sales-Data-Analysis-Python/
│
├── data/
│   └── retail_sales.csv
│
├── outputs/
│   ├── cleaned_retail_sales.csv
│   ├── category_summary.csv
│   ├── region_summary.csv
│   └── monthly_sales_summary.csv
│
├── visuals/
│   ├── 01_sales_profit_by_category.png
│   ├── 02_sales_by_region.png
│   ├── 03_monthly_sales_trend.png
│   ├── 04_monthly_profit_trend.png
│   ├── 05_discount_vs_profit_margin.png
│   ├── 06_profit_by_subcategory.png
│   ├── 07_sales_share_by_segment.png
│   ├── 08_shipping_days_by_mode.png
│   ├── 09_top_states_by_sales.png
│   ├── 10_profit_margin_by_category.png
│   ├── 11_quantity_vs_sales.png
│   └── 12_correlation_heatmap.png
│
├── retail_sales_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## How to Run

```bash
git clone https://github.com/mohammadkazi/Retail-Sales-Data-Analysis-Python.git
cd Retail-Sales-Data-Analysis-Python
pip install -r requirements.txt
jupyter notebook retail_sales_analysis.ipynb
```

## Portfolio Highlights

This project demonstrates:

- Practical data cleaning
- Exploratory data analysis
- KPI development
- Business-oriented analytics
- Data visualization
- Profitability analysis
- Trend analysis
- Actionable recommendations
- Reproducible Python workflow

## Business Insights

The final notebook automatically generates insights from the loaded dataset instead of hard-coding conclusions. This makes the project reusable with another retail dataset that follows the same column structure.

## Author

**Mohammad Sarim Kazi**  
Data & Business Analyst | Python | SQL | Power BI | Tableau

GitHub: https://github.com/mohammadkazi
