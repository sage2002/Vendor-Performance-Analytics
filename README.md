# Vendor Performance Analysis 📊

This project focuses on analyzing vendor performance using SQLite, Python (Pandas, NumPy, Matplotlib, Seaborn), Power BI and Jupyter Notebooks.
The goal is to evaluate purchase and sales data to identify vendor profitability, efficiency, and opportunities for improvement.

## Key Features 📈

Database Integration: Reads and processes data from inventory.db using SQL queries.

Vendor Summary Creation: Combines purchase, sales, and freight cost data into a single consolidated view.

Data Cleaning & Transformation: Handles missing values, removes inconsistencies, and creates calculated metrics such as:

Gross Profit

Profit Margin

Stock Turnover

Sales-to-Purchase Ratio

Exploratory Data Analysis (EDA): Identifies trends, correlations, and outliers in vendor performance.

Statistical Insights: Performs hypothesis testing to compare profit margins of top vs. low-performing vendors.

__Business Insights:__

Detects vendors needing promotional/pricing adjustments

Highlights impact of bulk purchasing on pricing and margins

Suggests strategies for both high-performing and low-performing vendors

## 📂 Project Structure  

```bash
├── data/                 # Input & processed datasets
├── logs/                 # Logging outputs
├── inventory.db          # SQLite database
├── ingestion_db.py       # Script for DB ingestion
├── get_vendor_summary.py # SQL queries & vendor summary creation
├── Exploratory Data Analysis.ipynb # EDA and insights
├── Vendor Performance Analysis.ipynb # Final analysis & visualizations
└── README.md             # Project documentation
```  

---

## 🛠 Tech Stack  

- **Python**: Pandas, NumPy, Matplotlib, Seaborn, SciPy  
- **SQL**: SQLite (via sqlite3 & SQL queries)  
- **Notebook**: Jupyter for interactive analysis & visualization  
- **Power BI**: Dashboard for:  
  - Vendor-level sales & profit drill-downs  
  - Trend analysis by brand & region  
  - KPI monitoring (Gross Profit, Margin %, Turnover Rate)  
  - Interactive filters for decision-makers  

---

## Example Insights  💻

- Vendors with bulk orders achieve **~72% lower unit costs**, improving margins.  
- Low-performing vendors maintain higher profit margins (premium pricing strategy) but lack sales volume.  
