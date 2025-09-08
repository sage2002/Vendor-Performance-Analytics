# Vendor Performance Analysis

This project focuses on analyzing vendor performance using SQLite, Python (Pandas, NumPy, Matplotlib, Seaborn), and Jupyter Notebooks.
The goal is to evaluate purchase and sales data to identify vendor profitability, efficiency, and opportunities for improvement.

🚀 __Key Features__

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

📂 Project Structure
├── data/                 # Contains datasets and exported CSV files  
├── logs/                 # Logging outputs for debugging and traceability  
├── inventory.db          # SQLite database with raw vendor data  
├── get_vendor_summary.py # SQL + Pandas pipeline to build vendor summary  
├── ingestion_db.py       # Utility for ingesting cleaned data back to DB  
├── Exploratory Data Analysis.ipynb  # Data cleaning + EDA  
├── Vendor Performance Analysis.ipynb # Final analysis & insights  

🛠️ Tech Stack

Python: Pandas, NumPy, Matplotlib, Seaborn, SciPy

SQL: SQLite (via sqlite3 & SQL queries)

Jupyter Notebook: Interactive analysis & visualization

Power BI Dashboard:

Vendor-level sales & profit drill-downs

Trend analysis by brand & region

KPI monitoring (Gross Profit, Margin %, Turnover Rate)

Interactive filters for decision-makers

📈 Example Insights

Vendors with bulk orders achieve ~72% lower unit costs, improving margins.

Low-performing vendors maintain higher profit margins (premium pricing strategy) but lack sales volume.

High-performing vendors may benefit from cost optimization and bundling strategies to increase margins.
