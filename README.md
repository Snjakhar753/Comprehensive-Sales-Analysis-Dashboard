# Internet Sales Management : Business Problem

## Dashboard Link: https://app.powerbi.com/groups/me/reports/50e5e93c-4b0e-4a44-a227-7aa23ca2f191/8860242b3a48af08b645?experience=power-bi

## 1.Aim :

--Business Request:
The project was initiated to create an executive sales report for sales managers, providing them with comprehensive insights into sales performance.

--User Stories:
To meet the business request, several user stories were defined to guide the development and ensure all acceptance criteria were met:

## 2. Data Overview: 
Microsoft AdventureWorks Database Analysis and Visualization with PowerBI. It's sample database, I chose 'AdventureWorksLT2019.bak' and 'AdventureWorksLT2017.bak' data for analysis & visualization. The query editing was done in 'Microsoft SQL Server Management Studio' and visualization part was using 'Microsoft Power BI'. Also for analysis I used MS Excel and PowerBI's query tool.
### --Schema :

1.  Fact Tables: Central tables containing quantitative data (e.g. FactInternetSales, FactResellerSales).

2. Dimension Tables: Descriptive attributes related to fact data (e.g. DimCustomer, DimProduct, DimDate).

## 3. Skills
1. Data cleansing and transformation(SQL Query and Power bi tools)
 2. ETL Processing
3. Data Modeling(ER Diagram)
4. SQL Server 
5. SQL Server Management Studio (SSMS-SQL engine)
6. Data Visualization(Power BI)
7. Dynamic KPIs
8. Data Analytics
9. MS Excel


 
## 4. Data Extraction Using SQL Server
Data is extracted from .sql files . And manupulated and Cleaned using SQL query (joins, aggregations, filtering etc.)
This involves following steps:

1. Data loading :

Dataset is loaded from Microsoft AdventureWorks (realstic data from "January/2021 - June/2024") in SSMS (SQL Srver Management Studio).

2. ETL Processing:  
Data cleansing and transformation are crucial steps in the ETL (Extract, Transform, Load) process, ensuring data quality and preparing it for analysis. These steps involve identifying and correcting errors, standardizing data formats, and converting data into a suitable structure for analysis.

3. Data Extraction:
After the cleansing process now data is ready for the analysis and data is extracted from SQL server into Common Separated File format(.csv file) to further analysis in the power BI.

Now we have following dataset file (Table) for the analysis:

1. Customer table:
![table1](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/31e984ba-5403-4bdf-b991-aced066841b8)

2. Calender table:
![table2](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/780fcfa4-2420-4c6c-8d71-4c6ca992efae)

3. Product table:
![table3](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/c85c62e5-64df-48ce-b0d7-a1bbdcb18fa3)

4. Internet Sales table:
![table4](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/50a9729a-4e83-487e-8ae9-570dfa982c66)

5. Budget Table: Data source which is provided by the resources and containing data from 2021-2024.
![table5](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/94f29384-1e33-4513-89a0-d3d0664d250a)

-- Fact Table :Central tables containing quantitative data -
"Internet Sales table".

--Dimension Table :Descriptive attributes related to fact data -
"Customer, Calender, Product Table".

## 5. Data Modeling :

Using power BI desktop we create the relationship between fact table and Dimension table by foreign key . 

Fact tables have many-to-one relationships with dimension tables, using foreign keys to reference dimension tables.

### Entity Relationship Diagram Model

![Model_4](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/02c3b553-5058-4960-b05a-65adeb2e4c32)

## 6. Measurments and Calculations:
Using aggregate function (SUM, AVG etc) in Power BI we create different new Measurments for understanding the sales data and budget.Sales and budget are work as key Performance Indicator(KPIs) for sales analysis. We find the different values for further analysis as:

Sales : which gives the total sale amount , which is calculated form Internet sales table. Then we calculate the sales amount per month , sales amount per customer etc.

Budget : which give the total budget of company , which is calculated form budget data provided by company.

## 7 Data visualization :(Power BI)
To analyze sales data to provide actionable insights for sales managers, highlighting trends, performance metrics, and areas for improvement.
### Sales Overview DASHBOARD
![Sales Overview_1](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/cffc6ad9-3a4b-4085-9ea6-3df339a113f2)

### Customer Details DASHBOARD
![customer](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/7e2d1ebe-8975-4332-a114-ccd1866bb040)

###  Product Details DASHBOARD
![product](https://github.com/Snjakhar753/Comprehensive-Sales-Analysis-Dashboard/assets/122297111/3ce29bad-f8be-4afc-940d-c12c2358f576)


## 8.Conclusion:
To understand and  identify the sales trends to provide valuable insights into our business scenario we recommend these area for making the business more profitable :

--Dominance of Product Top 10 products suggests opportunities for further product development and marketing strategies to capitalize on its popularity.

--Also we mention the Top 10 customer as  more a business can retain satisfied customers, the better it is for their long-term growth and generating customer retention leads.

-- To improve the sales focus on marketing efforts around peak sales periods to maximize revenue.
