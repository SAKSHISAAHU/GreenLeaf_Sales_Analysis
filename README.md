# GreenLeaf Sales Analysis 

### 📌 About GreenLeaf 
- It manufactures and distributes a diverse portfolio of packaged foods and beverages. There business model combines in-house manufacturing with regional distribution, enabling them to serve distributors, modern and traditional retail outlets, as well as a select group of direct accounts. They operate through a structured sales organization (Salesperson → Supervisor → Manager) and track sales at the transactional order-line level.

### 🎯 Objectives
- The project analyzes GreenLeaf’s sales performance across products, channels, and teams. By studying historical transaction data, the analysis uncovers sales patterns, highlights growth opportunities, and addresses inefficiencies. The goal is to translate raw sales data into actionable insights that guide portfolio optimization, strengthen channel strategies, and drive overall business growth.

### 📊 Dataset Summary
- Time Period: Jan 2019 – Mar 2021
- Records:
    - 798 records in Product Table
    - 260K+ records in Sales Table
- Columns:
    - 4 columns in Product Table
    - 10 columns in Sales Table

### 🛠️ Tools & Technologies Used
- Excel – Raw data source
- Power BI – Data modeling & dashboarding
- Power Query - Data Cleaning & Transformation

### 🔄 ETL Workflow
    Excel File  
        │  
        ▼  
    Load into Power BI  
        │  
        ▼  
    Data understanding
        │  
        ▼
    Data modeling
        │  
        ▼
    Data Exploration  
    (Check missing values, duplicates, data types, schema)  
        │  
        ▼  
    Data Cleaning  
    (Fix column names, correct date type, establish relationships)  
        │  
        ▼  
    Data Transformation  
    (Merge Product + Sales → Final Sales table)  
        │  
        ▼  
    Feature Engineering  
    (Create Sales column, drop unneeded fields)  
        │  
        ▼  
    Clean & Ready Dataset for Analysis  

### 📈 Visualizations & Insights
- Top Product Groups: Wheat Flour (4.5M), Oil (2.9M), Yeasts (2.2M).
- Bottom Product Groups: Tomato Sauce, Tea, Cassava Starch, Red Wine, Energy Drink.
- Category Split: Food = 91.39% of sales, Drinks = 8.61%.
- Channel Contribution: Retail (48.56%), Distributor (34.05%), Online (17.39%).
- Sales Trend: Growth from 2019–2020, peak in Oct 2020 (3.2M), decline in early 2021.
- Top Salesperson: Carla Ferreira ($4.7M).
- Top Manager: Gabriel Azevedo ($9.2M).

### 📎 How to Use
- Open Greenleaf_Sales.pbix in Power BI.
- Now explore the interactive dashboard and insights.

### 👩🏻‍💻 Author - Sakshi Sahu (Data Analyst)