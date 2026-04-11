🧠 Project Title:
Optimized Thrift Intelligence System


📌 Problem:
Thrift businesses often struggle to identify which products generate the most profit, which items sell fastest, and whether their revenue is driven by **high margins or high sales volume**. Without structured data analysis, decision-making around inventory, pricing, and sourcing becomes inefficient.


⚙️ What This Project Does:

* Generates a structured thrift dataset using Python
* Stores and manages data using SQL (MySQL)
* Performs exploratory data analysis (EDA) using Pandas

Calculates key metrics:

  * Revenue
  * Cost
  * Profit
  * Average Days to Sell

Identifies:

  * Top-performing categories
  * Fastest-selling items
  * Most profitable sourcing strategies
  * Visualizes insights through an interactive Power BI dashboard


📊 Sample Output:

Power BI Dashboard:
![Dashboard Screenshot](images/Screenshot%202026-04-10%20205647.png)


💡 Key Insights:

* Topwear generates the highest total profit → should be prioritized in inventory scaling
* Sneakers and T-Shirts sell fastest → ideal for quick cash flow strategies
* Supplier-sourced products yield the highest total profit → supplier relationships are key
* Some items rely on volume rather than margin → pricing strategies can be optimized


🛠️ Tools Used:

* Python
* Pandas
* MySQL
* Power BI


📁 Project Structure:

dashboard/
    thrift_dashboard.pbix

data/
    raw/
        thrift_data.csv

images/
    Screenshot 2026-04-10 205647.png

notebooks/
    01_data_generation.ipynb
    02_eda.ipynb
    03_sql_integration.ipynb

README.md


🚀 How to Run This Project:

1. Clone the repository
2. Install required Python libraries:

   pip install pandas mysql-connector-python
   
3. Run notebooks in order:

   * Data Generation
   * EDA
   * SQL Integration
4. Open Power BI file (`.pbix`) to explore dashboard


🎯 Project Outcome:
This project demonstrates an **end-to-end data analytics workflow**, from data generation and storage to analysis and business intelligence, enabling data-driven decision-making for a thrift business.