Retail Sales Data Analysis — Python
📊 Overview
An end-to-end retail sales analytics project built with Python, Pandas, NumPy, Matplotlib, and Seaborn. The workflow covers data loading, data-quality checks, cleaning, feature engineering, KPI analysis, category and regional performance, customer segments, shipping performance, discount impact, and business recommendations.
> **Data note:** The current repository does not contain `data/retail_sales.csv`, so the notebook falls back to its deterministic demo dataset (`n=4500`, `seed=42`). The results below are therefore the **actual outputs of the repository's current fallback dataset**, not a claim about an external retail dataset.
🎯 Business Questions
What are the overall sales, profit, orders, and average order value?
Which categories generate the most sales and profit?
Which regions perform best?
How does discounting affect profitability?
Which customer segment contributes the most sales?
Which shipping modes are used most?
Which areas need management attention?
🔄 Workflow
```text
Raw Data
   ↓
Data Quality Audit
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
KPI Analysis
   ↓
Category / Region / Segment Analysis
   ↓
Discount & Shipping Analysis
   ↓
Visualizations
   ↓
Business Recommendations
```
📌 Current Repository Output
Executive KPIs
KPI	Output
Total Sales	₹4,884,097.80
Total Profit	₹503,359.73
Unique Orders	4,500
Units Sold	17,950
Average Order Value	₹1,085.36
Overall Profit Margin	10.31%
Average Discount	16.74%
Average Shipping Days	3.43
Category Performance
Category	Sales	Profit	Profit Margin
Office Supplies	₹1,926,059.35	₹216,680.11	11.25%
Technology	₹1,621,032.04	₹243,954.52	15.05%
Furniture	₹1,337,006.41	₹42,725.10	3.20%
Observation: Technology has the highest profit and strongest margin, while Furniture has the weakest margin in the current demo dataset.
Regional Performance
Region	Sales	Profit	Orders
East	₹1,273,396.96	₹131,740.68	1,136
West	₹1,214,870.27	₹124,268.33	1,131
Central	₹1,203,830.42	₹125,495.09	1,116
South	₹1,192,000.15	₹121,855.63	1,117
Customer Segment
Segment	Sales	Profit	Sales Share
Consumer	₹2,654,256.35	₹264,195.92	54.34%
Corporate	₹1,382,021.80	₹144,485.22	28.30%
Home Office	₹847,819.65	₹94,678.59	17.36%
Discount vs Profitability
Discount Band	Profit	Average Margin
0–10%	₹309,867.42	14.10%
10–20%	₹183,932.05	9.26%
20–30%	₹14,219.06	3.55%
30–40%	-₹915.19	-0.76%
40%+	-₹3,743.61	-5.67%
Business takeaway: In this demo dataset, profitability declines sharply as discounts increase, with the 30%+ discount bands producing negative average margins.
🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
📁 Project Structure
```text
Retail-Sales-Data-Analysis-Python/
├── data/
│   └── retail_sales.csv
├── outputs/
├── visuals/
├── retail_sales_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```
🚀 Run Locally
```bash
git clone https://github.com/mohammadkazi/Retail-Sales-Data-Analysis-Python.git
cd Retail-Sales-Data-Analysis-Python
pip install -r requirements.txt
jupyter notebook retail_sales_analysis.ipynb
```
⚠️ Portfolio Note
Before using the KPI numbers as portfolio claims, replace the fallback demo dataset with a real dataset and rerun the notebook. The notebook is intentionally designed to generate a labelled demo dataset when the CSV is unavailable.
👤 Author
Mohammad Sarim Kazi  
Data & Business Analyst | Python | SQL | Power BI | Tableau
