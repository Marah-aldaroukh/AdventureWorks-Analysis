📊 AdventureWorks Sales & Profit Analysis
📌 Project Overview
This is an end‑to‑end data analysis project of AdventureWorks Cycles, a fictional bicycle manufacturer. The dataset covers sales, customers, products, and returns from 2015 to 2017.
The project demonstrates the full data analysis workflow:

SQL – Data extraction, cleaning, and integration.

Python – In‑depth statistical analysis, regression modeling, and outlier detection.

Power BI – Interactive dashboard creation for visual insights.

🔍 Key Findings
Premium products (24.8% of transactions) generate 92.3% of total profit, despite their lower sales volume.

Sales show consistent annual growth, with a strong peak every December (holiday season).

Accessories (water bottles, helmets, tires) have the highest return volumes, but premium products cause larger financial losses per return due to their high prices.

A multiple linear regression model confirms a perfect linear relationship between profit and (quantity, price, cost) – R² = 1.0.

Geographic analysis reveals that US regions (Southwest, Northwest) outperform others, while Australia and the UK show untapped potential.

🛠️ Tools & Technologies
Tool	Purpose
SQL	Data cleaning, table joins, preparation
Python	Statistical analysis, regression, decision trees, visualizations (Pandas, Matplotlib, Seaborn, Scikit‑learn)
Power BI	Interactive dashboards, DAX measures, 
GitHub	Version control and portfolio hosting
📂 Repository Contents
text
AdventureWorks-Analysis/
│
├── data/                       # Sample CSV files (optional, see note below)
├── sql_scripts/                 # SQL scripts for database creation & cleaning
├── adventureworks_analysis.ipynb # Full Jupyter notebook (Python analysis)
├── dashboard.pbix                # Power BI dashboard file
├── report.pdf                    # Final analysis report (Arabic/English)
├── images/                       # Visualizations used in the report
└── README.md                     # This file
Note: The full raw data is not included due to file size constraints. You can download it from the original Kaggle source (AdventureWorks sample datasets). The sql_scripts/ folder contains the necessary structure to rebuild the database.

🚀 How to Run
1. Clone the repository
bash
git clone https://github.com/Marah-aldaroukh/AdventureWorks-Analysis.git
2. Set up the database
Install MySQL Server and MySQL Workbench.

Run the scripts in sql_scripts/ (in order) to create the adventureworks database and load the sample data.

3. Run the Jupyter notebook
Install required Python libraries:

bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels mysql-connector-python
Open adventureworks_analysis.ipynb and execute all cells.

4. Explore the Power BI dashboard
Open dashboard.pbix in Power BI Desktop.

If needed, update the database connection (localhost/root/password) under Get Data → MySQL.

📬 Contact
For questions, collaboration, or feedback, feel free to reach out:
Email: marahmaroo72001@gmail.com
GitHub:Marah-aldaroukh

This project is for educational purposes. All data used belongs to Microsoft’s AdventureWorks sample databases.

