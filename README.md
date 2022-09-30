# **Sales_Insights**
Fully automated and interactive Microsoft Power BI dashboard that facilitates easy interpretation of sales data. 


## **Overview**
This project was designed to assist the sales directer at AtliQ Hardaware with navigating through a challenging and dynamically changing market. This has been achieved by creating a fully automated and interactive dashboard that will provide the sales directer with necessary insights in real-time to asses the company's performance and device the appropriate strategy based on the data. 


## **Tech Stack**
* SQL
* PostgreSQL
* Microsoft Power BI


## **Methods**

#### **SQL**
Utilized SQL statements to create a database consisting of 5 tables (customers, date, markets, products, and transactions) and SQL queries to perform exploratory data analysis.

#### **Microsoft Power BI**

**ETL (Extract Transform Load)**

Established a connection between the postgres database and Power BI to import the data.

Modelled the data by establishing a connection between the main table 'transactions' with the remaining tables.

Created additional measures (Revenue, Sales Qty, Profit Margin, Total Profit Margin %, Profit Margin Contribution %, and Revenue Margin Contribution %)  utilizing DAX.

Cleaned the data by:
* Removing duplicates
* removing any records from sales_amount that was 0 or negative.
* creating a new column (norm_sales_amount) that holds all sales amounts in Rupees.

## Dashboard
Finally, a fully interactive dashboard which is connected to the database to facilitate real-time updates was created.

![Dashboard_Photo](https://github.com/OmarQasem94/Belly_Button_Biodiversity/blob/main/static/images/Dashboard.PNG)

The dashboard depicts the following KPIs:

* Revenue
* Sales Quantity
* Profit Margin 
* Profit Margin %
* Profit Margin % per Market
* Profit Contribution % per Market
* Revenue Controbution % per Market
* Profit Margin % per Customer
* Profit Contribution % per Customer
* Revenue Controbution % per Customer
* Revenue Trend
* Year and month filtering
