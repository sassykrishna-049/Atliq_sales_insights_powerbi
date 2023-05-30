# Atliq Sales Insights PowerBI Dashboard

This is a project I replicated from Codebasics PowerBI Channel.You can find the link of the playlist below.

[Codebasics Youtube PLaylist](https://www.youtube.com/playlist?list=PLeo1K3hjS3uva8pk1FI3iK9kCOKQdz1I9)


## Problem Statement
AtliQ Hardware is a business with numerous branches across India that provides computer hardware & peripheral products to its customers. Bhavin Patel, company's sales director is having a difficult time figuring out how the company is doing and what all of its problems are.Sales are not increasing as anticipated and are already decreasing. Additionally, as a result of human nature, if the sales director calls the regional managers to inquire about the state of the market and sales, they tend to sugarcoat the information and provide a tons of Excel files rather than providing the straight story, which only served to aggravate the sales director.
The obvious cause of the annoyance is that people find it uncomfortable to read numbers from Excel files.


## Solution
Sales Director of the Atliq Hardware, decided to build a PowerBI Dashboard for converting data into visual representation  to make data driven decisions. SO he hired a Data Analyst to complete this task for him.

## AIMS(Advance Industrial Mailing System) Grid
[AIMS grid](https://www.linkedin.com/pulse/aims-grid-bulls-eye-project-management-tool-data-analysts-ramesh/) is a very useful tool to improve Project Management skills for Project managers, Team Leaders etc. It helps to clarify a task and keep the process simple. AIMS grid presents a project in a very concise manner.

![Alt text](https://github.com/sassykrishna-049/Atliq_sales_insights_powerbi/blob/main/Dataset/AIMS.jpg)

## Steps Followed in this project

1. Performed a High level analysis of data in SQL to get better understanding over the data.
2. Connected the SQL data set to PowerBI.
3. Performed ETL and data cleaning on the imported data.
4. In the currency there were two types of currencies i.e INR and US Dollar, in transactions, performed currency conversion to make all the currency type same.
5. Created measure as needs and used them for creating visuals in PowerBi.
6. After the initial report reviewed by the stakeholders, made changes to the report based on the review got.

## Data Transformation Performed
1. In the market table, "zones" column , we removed the null values
2. In the Transactions table, there were some garbage values(0,-1) in the " sales_amount" column , so we had to remove them.
3. In the Transactions table, " currency" column there were 2 types of currency so we converted them to INR.
4. Also removed the duplicate entries from the transaction table

## Final Result 

### Initial Dashboard
![Alt text](https://github.com/sassykrishna-049/Atliq_sales_insights_powerbi/blob/main/Dataset/Initial%20SS.png)





