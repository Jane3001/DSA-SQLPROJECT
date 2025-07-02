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
     ![SQL Question 1](https://github.com/user-attachments/assets/51658501-b992-4538-adb3-6ca9cf45aeb0)
   
 - What are  the  Top 3 and Bottom 3 regions in terms of sales?
   ![SQL Question 2](https://github.com/user-attachments/assets/bfa69770-1194-4600-8bc3-e445b8f13967)
   
 - What  were the total  sales  of  appliances  in  Ontario?
   ![SQL Question 3](https://github.com/user-attachments/assets/afb025ec-5f83-478c-888c-ca7aa646aec9)
   
 - Advise  the  management  of  KMS  on  what  to do to increase the revenue from the bottom 10  customers
   ![SQL Question 4](https://github.com/user-attachments/assets/cc38ba65-4051-4d7d-91d4-648539625ac8)
   
 - KMS incurred  the  most shipping  cost  using  which  shipping  method?
   ![SQL Question 5](https://github.com/user-attachments/assets/4f5c20f4-3d9e-4615-964e-c466a7801b5f)
   
#### Case  Scenario  II 
 - Who  are  the  most  valuable  customers,  and  what  products  or  services  do  they  typically purchase?
   ![SQL Question 6](https://github.com/user-attachments/assets/2491ebe2-03f3-44bf-9b73-5847127a300c)
   
 - Which  small  business  customer  had  the  highest  sales
 ![SQL Question 7](https://github.com/user-attachments/assets/50812dcc-8ec4-4e4c-b1cd-ab90ead03ff0)

 - Which  Corporate  Customer  placed  the  most  number of orders  in  2009 – 2012?
   ![SQL Question 8](https://github.com/user-attachments/assets/d8f73155-c4a0-4a2e-a1d4-0f42c9026ee3)
   
 - Which  consumer customer was the most profitable one?
   ![SQL Question 9](https://github.com/user-attachments/assets/5b4b564e-0618-423d-b885-43e90896ad46)
   
 - Which  customer  returned  items,  and  what  segment  do  they  belong  to?
   ![SQL Question 10](https://github.com/user-attachments/assets/82fb8cb9-cde0-406e-b0d9-b6939a31e1b8)
   
 - If  the  delivery  truck  is  the  most  economical  but  the  slowest  shipping  method  and Express  Air  is  the  fastest  but  the  most  expensive  one,  do  you  think  the  company appropriately  spent  shipping  costs  based  on  the  Order  Priority?  
![SQL Question 11](https://github.com/user-attachments/assets/cc7dfe77-8dc0-4d20-8291-892a1903dd9b)

### Data Analysis 
![SQL Query 1](https://github.com/user-attachments/assets/6453469c-815c-45e0-9ff0-530968c53ea0)

![SQL Query 2](https://github.com/user-attachments/assets/7610aa39-3fad-4e14-904d-ba62b6b8c293)

![SQL Query 3](https://github.com/user-attachments/assets/93a48897-4789-4f69-989c-9923661ec2fb)



