# customer-trends-data-analysis-SQL-Python-PowerBI

Customer Shopping Behaviour Analysis
📌 Overview

This project aims to analyze customer shopping patterns to understand purchasing behavior, spending trends, and product preferences. The analysis helps businesses make informed decisions regarding inventory planning, marketing strategies, and customer segmentation.

The workflow includes data loading, cleaning, EDA in Python, SQL analysis, dashboard creation in Power BI, and generating a final business insights report.

📂 Dataset

Source: Kaggle

Dataset Type: Customer shopping transactions

Content: Contains customer demographic details, purchase behavior, category preferences, and spending value.

🛠 Tools & Technologies Used
Purpose	Tool
Data Loading & EDA	Python (Pandas, NumPy, Matplotlib, Seaborn)
Data Cleaning	Python
Database Querying	PostgreSQL / MySQL / SQL Server
Dashboard & Visualization	Power BI
Reporting	Gamma App
Version Control	Git & GitHub
🔧 Project Workflow Steps
1. Data Loading

Loaded dataset using Pandas

Displayed dataset info and initial statistics

2. Data Cleaning

Handled missing values

Removed duplicates

Standardized column formats

Checked and fixed data consistency issues

3. Exploratory Data Analysis (EDA)

Explored customer demographics and purchase behavior

Identified product category purchase frequency

Visualized trends and correlations

4. SQL Analysis

Performed SQL queries to extract deeper insights such as:

Most purchased product categories

Repeat customer purchase frequency

Weekend vs weekday transaction comparison

5. Power BI Dashboard

Developed an interactive dashboard containing:

Average Spend per Customer

Top Product Categories

Customer Demographic Breakdown

Filters for Category, Gender, and Customer Type

6. Business Report (Gamma)

Summarized insights, visual snapshots, and recommendations for business decision-making.

📊 Key Insights

Certain product categories are most popular, indicating strong consumer preference patterns.

Weekend shopping trend observed, showing higher transaction volume during weekends.

Repeat customers have higher purchase value, suggesting customer loyalty contributes significantly to revenue.

Average spend per customer provides useful segmentation for targeted marketing strategies.

▶️ How to Run

Clone the repository:

git clone https://github.com/yourusername/Customer-Shopping-Behaviour-Analysis.git


Install dependencies:

pip install -r requirements.txt


Run the Jupyter Notebook for EDA & Cleaning.

Import cleaned data into your SQL database for query execution.

Open the Power BI file to explore the dashboard.

Review the final Gamma report for insights and presentation.

📁 Project Structure
|-- data/                     # Raw and cleaned datasets
|-- notebooks/                # EDA & cleaning notebook
|-- sql/                      # SQL query scripts
|-- dashboard/                # Power BI dashboard (.pbix)
|-- report/                   # Gamma report / summary
|-- README.md                 # Project documentation
