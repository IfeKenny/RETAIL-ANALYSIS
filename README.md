# RETAIL-ANALYSIS
Retail analysis contains dataset spanning multiple categories, which include: Invoice No, Stock Code, Description, Quantity, Invoice Date, Unit Price, Customer ID, and Country. 
Data Cleaning & Preparation
•	Handling Missing Values: The dataset originally had 1,454 missing entries in Description and 135,080 missing entries in Customer ID. These null values were filled with the string "0". 
•	Duplicates: The dataset contained 5,268 duplicate rows and the duplicates was removed using Retail.drop_duplicates()
•	A new column named Revenue was calculated by multiplying Quantity by Unit Price. And a Month column was also extracted from Invoice Date to analyze trends. 
Key Insights
Top 5 Best-Selling Products (by Revenue): DOTCOM POSTAGE and REGENCY CAKE STAND 3 TIER are the highest revenue generators and best-selling products by revenue
Top 5 Revenue-Generating Countries
The vast majority of the company's revenue comes from the United Kingdom with 8,187,806.36
Monthly Sales Trends
The monthly revenue trends started with December 2010 ($748,957.02) and dropping into January 2011 ($560,000.26) and February 2011 ($498,062.65).
[Kehinde_OkewoleAnalystlab.ipynb](https://github.com/user-attachments/files/28911606/Kehinde_OkewoleAnalystlab.ipynb)
