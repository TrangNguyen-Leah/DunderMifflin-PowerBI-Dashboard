# DunderMifflin-Sales-Analysis
## Project Overview
Dunder Mifflin is a provider of essential office supplies for businesses, organizations, and individuals. This project aims to use Business Intelligence in Power BI to identify and analyze sales challenges, offering decision-makers actionable insights for business improvement.

Link to dataset on Github: [here](https://github.com/tdmitch/DunderMifflin/tree/master).

<p align="center">
  <img src="https://github.com/TrangNguyen-Leah/DunderMifflin-PowerBI-Dashboard/blob/main/Dunder%20Mifflin%20logo.png">
</p>

**Course**: Business Intelligence

**Institution**: University of Economics Ho Chi Minh City (UEH) - School of Technology and Design

## Project Objective
The main objective of this project is to analyze:
- Business performance
- Human resource management effectiveness
- Transportation activities
- Supply chain and warehouse management efficiency
- Customer loyalty

## Methodology
### 1. ETL Process:
**Extract**: We used SQL to merge text files from the Dunder Mifflin dataset on GitHub.

**Transform**:

We used Power Query Editor for data cleaning and preprocessing, followed by Python to visualize the distribution of each column:
- Removed unnecessary tables and ambiguous columns, such as the Regions table, EmployeeRegions table, and People table.
- Handled missing values in certain fields by replacing them with appropriate default values or means.

**Load**: The transformed data was loaded into Power BI for further analysis and visualization.
  
### 2. Data Modeling:
Created galaxy schema with 2 fact tables (Orders, OrderDetails) and 8 dimensions (Products, Categories, Suppliers, Customers, OrderLocation, Shippers, Employees and EmployeeStatus) to store structured information.

<p align="center">
  <img src="https://github.com/TrangNguyen-Leah/DunderMifflin-PowerBI-Dashboard/blob/main/data%20model.png" alt="Dunder Mifflin Data Modeling">
</p>  

Implemented transformations to align the data structure with Power BI's analytical capabilities.

### 3. Analysis:
Link to Full Dashboard and Reports: [here](https://github.com/TrangNguyen-Leah/DunderMifflin-PowerBI-Dashboard/blob/main/Sales%20Analysis%20dashboards.pdf)


## Key Insights
- **Business Performance**:
  + The demand for office supplies has decreased because of COVID-19.
  + High-revenue products are no longer being produced, leaving only low-revenue items for sale.
  
- **Customer loyalty**: 
Dunder Mifflin doens't offer special discount programs for regular customers.

- **Shipper Performance**: 
  + The company manages a small number of orders on its own.
  + Orders are often delivered late.
  + The order processing is overwhelmed.
   
- **Employee Analysis**:
  + The organization is divided into too many small departments.
  + There is a heavy reliance on certain departments.
  + The workforce lacks young employees who can catch up with newest market trends.
  + The employee rehiring rate is low, at 5 out of 47.
  + Employee performance varies significantly across the company.
  
- **Uneffective supply chain and warehouse management**:
  + The organization has too many small departments.
  + There is a strong reliance on specific departments.
  + The workforce lacks younger employees who can keep up with the latest market trends.
  + The rehire rate for employees is low, with only 5 out of 47 returning.
  + Employee performance varies greatly across the company.
    
## Tools and Technologies
- **SQL**: Used for data extraction.
- **Python**: Used for data analysis. 
- **Power BI**: Used for transforming, cleaning and visualizing data, which helped identify valuable insights. 
