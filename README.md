# Data modeling project(Meta Database Engineering)
A data modeling project for Global Super Store.
Scenario
Global Super Store have collected huge amounts of data from their business operations within the USA. This data has been collected in an excel sheet with the following data fields: 
Order ID and Order Date.
Ship Date and Ship Mode.
Total Cost and Product Price.
Customer ID, Name and Contact Details. 
City, State, Country and Postal Code.
Product ID, Category and Sub-Category.
Product Name and Quantity.
Discount, Shipping Cost and Order Priority.

Global Super Store want to restructure their database system in a proper database management system within MySQL. They also want to analyze existing data to understand their business performance and progress. 
Help Global Super Store to restructure and analyze their database by carry out the following tasks.

Instructions
To complete these tasks, you need to use MySQL Workbench for database modeling and Tableau for data analysis. 

Step 1: Create an ER diagram
Your first task is to use the visual data modeling tool in MySQL Workbench to create a suitable ER diagram for the Global Super Store. 
Make use of the data fields within the company Excel file as stated in the scenario. Feel free to add more entities and attributes if required. Make sure that your tables are normalized to conform with the three fundamental normal forms. 

Step 2: Implement the data model
Use MySQL Workbench’s forward engineer feature to implement the Global Super Store data model inside MySQL server.

Step 3: Create a star schema
The marketing department at the Global Super Store Company want to build a campaign to promote the company’s products within the USA. 

First, they need to understand the company’s performance in this market by analyzing their sales data. They are interested in data related to products, locations and times only. 

Help them out by creating a Star schema that includes relevant fact and dimensions tables with relevant attributes and data types.

Step 4: Create a map chart
Use Tableau to investigate Global Super Store’s sales in the USA. Create a map chart that shows sales in different states within the USA. 

If you rollover a state, then you should be able to view the state name and sales figure as shown below.
https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/ZgZowldpSZySWgfs87HEGA_6a8f7f1829754af1a3c1f890c673aee1_C7M4L1-Item-3-img-1.png?expiry=1687737600000&hmac=CFW8CtnsynMcA0eNZIKllY0pNcLKt0TbFRr8ILyVzqo
![image](https://github.com/Celine0k0y3/DB_Project/assets/122078188/4f3f2c62-1e08-46d6-b240-16116f053a23)


Step 5: Create a bubble chart
The Global Super Store needs to check their profits within the USA. To help them out, create a bubble chart in Tableau. Call it “Profits in USA”. 
If you rollover a bubble, you should be able to view the following information, as shown in the screenshot below:
State name,
Quantity sold,
Profits,
and shipping cost. 
https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/Lrbi5wsZTQ-4YTyrkGT6AA_87353fb0f08849abbe99c61e7209dfe1_C7M4L1-Item-3-img-2.png?expiry=1687737600000&hmac=ct8n_RAfy7jm3T-hiAaykIfLRzqumy1QBVPcn552fD8

![image](https://github.com/Celine0k0y3/DB_Project/assets/122078188/6fa1df2d-5695-4942-821e-15448264ad4e)


Step 6: Create a line chart
The Global Super Store want to view sales trends in the USA over the last 4 years. Create a line chart in Tableau for states with Sales of more than $40000. Call it “Sales Trend in USA”, as shown below. 
https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/o-H7V-nXTUyh3GSf_4sdCw_df9e11980ee14d529fe0a3ac9e2ff0e1_C7M4L1-Item-3-img-3.png?expiry=1687737600000&hmac=zra0X1yLyIxJXb5HK2Pm6MnP1Z0BPjJEPKSYBoJya0I
![image](https://github.com/Celine0k0y3/DB_Project/assets/122078188/a708f3a0-9bca-4ad9-831c-36f78e383ca4)

Step 7: Create an interactive dashboard
Create an interactive dashboard that includes the charts produced in tasks 4, 5 and 6. Name it ‘Sales and Profits in the USA’. If you click on a state, you should be able to view relevant sales and profits information as shown below.
https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/nuZ09c5ERSep8BhmoiZ7Sg_f96eaa8e6acd47049b3c175ffd1298e1_C7M4L1-Item-3-img-4.png?expiry=1687737600000&hmac=Gv1_eCFpyWbfdbAD9p1_MeiqnSrzJsmWyHDugwEA41A
![image](https://github.com/Celine0k0y3/DB_Project/assets/122078188/7b9094c3-53cb-4ee4-8aa9-9b38f4ab2c1a)


You can now create an ER diagram for Global Super Store and use MySQL Workbench’s Forward Engineer feature to implement the ER diagram in a MySQL database. You also know how to develop a dimensional data model for the Global Super Store. You can also analyze data with relevant charts using Tableau and build an interactive dashboard.

Disclaimer: This is for my Project on Advanced Data Modeling(Meta Database Engineering Specialization). 
I did not create nor take part in creating this question, attached are my own attepts(my project).
