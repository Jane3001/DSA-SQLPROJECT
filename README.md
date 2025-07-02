# DSA-SQL PROJECT
My first project on SQL, using skills acquired from DSA training
## Project Topic: KMS Sales Analysis

### Project Overview
The aim of the project is to analyze the sales and order data from KMS to gain insights that can help the Abuja Division. Using SQL, the analysis identifies top customers, best-selling products, shipping cost efficiency and reginal sales trend. The information gathered is to help KMS optimize sales strategies, reduce logistics costs and better understand customer behaviour based on historical data from 2009 to 2012

### Data Sources 
The dataset used is KMS SQL Case Study.csv. It was provided by our trainer in Digital Skillup Africa(DSA). The dataset contain order records for Kultra Mega Stores covering the period 2009 to 2012.

### Tools Used 
- Microsoft Excel (for cleaning)
- SQL Server (for querying and analysis)

### Data Cleaning and Preparation 
- File inspection and formatting 
    - Checked for duplicates
    - Checked for missing headers 

- Column name standardization 
    - Renamed columns to remove spaces and special characters (e.g Order Date → Order_Date).
    - Ensured consistent casing.
- Data type conversion 
    - Converted dates (OrderDate) to proper DATETIME format.
    - Cast numeric fields like Sales, Profit, and Shipping Cost to  DECIMAL 
    - Ensured text fields (CustomerName, Segment, etc.) were stored as VARCHAR.
- SQL Server Import
    - Imported the cleaned dataset into SQL Server.
    - Validated row counts and data integrity post-import.

### Exploratory Data Analysis 
#### Case  Scenario  I 
 - Which  product  category  had  the  highest  sales?
 - What are  the  Top 3 and Bottom 3 regions in terms of sales?
 - What  were the total  sales  of  appliances  in  Ontario? 
 - Advise  the  management  of  KMS  on  what  to do to increase the revenue from the bottom 10  customers 
 - KMS incurred  the  most shipping  cost  using  which  shipping  method? 
#### Case  Scenario  II 
 - Who  are  the  most  valuable  customers,  and  what  products  or  services  do  they  typically purchase?
 - Which  small  business  customer  had  the  highest  sales?
 - Which  Corporate  Customer  placed  the  most  number of orders  in  2009 – 2012?
 - Which  consumer customer was the most profitable one?
 - Which  customer  returned  items,  and  what  segment  do  they  belong  to?
 - If  the  delivery  truck  is  the  most  economical  but  the  slowest  shipping  method  and Express  Air  is  the  fastest  but  the  most  expensive  one,  do  you  think  the  company appropriately  spent  shipping  costs  based  on  the  Order  Priority? 

### Data Analysis 
