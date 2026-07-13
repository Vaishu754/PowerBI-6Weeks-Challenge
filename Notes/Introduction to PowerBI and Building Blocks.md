 Introduction to Power BI

## Topics Covered
- Introduction to Power BI
- Installing Power BI Desktop
- Building Blocks

## 1) What is Power BI?
Power BI is a business intelligence and data visualization tool by Microsoft.
It helps us connect data, clean data, analyze data, and create interactive dashboards.
It is launched in 2015

## 2) Why do we use Power BI?
- To convert raw data into visuals
- To create reports and dashboards
- To analyze business performance
- To share insights with others

## 3) Building Blocks of Power BI
1) Visualizations
Meaning:
Visualizations means charts, graphs, tables, cards, maps that show data in a clear way.

Why we use it:
Instead of reading raw numbers in rows and columns, we can understand data quickly using visuals.

Examples of visuals in Power BI:

Bar chart → compare sales of different products
Line chart → show sales trend month by month
Pie chart → show percentage share
Table / Matrix → show detailed data
Card → show one important value like Total Sales
Map → show location-wise data

Simple example:
If a company has sales data, visualization helps answer:

Which product sold the most?
In which month sales were high?
Which city gave more profit?

2) Modeling
Meaning:
Modeling means creating relationships between different tables and preparing data properly for analysis.

In simple words:
If you have multiple tables like:

Customers table
Orders table
Products table

You connect them using common columns like:

Customer ID
Product ID
Order ID

This connection is called data modeling.

Why it is used:

To combine data from different tables
To avoid duplicate work
To make reports accurate
To calculate results easily

Example:
If Orders table has Customer_ID and Customers table also has Customer_ID, we connect them.
Then we can know:

Which customer placed which order
Total sales by customer
Orders by city

Important things in modeling:

Relationships
Primary key / foreign key
Star schema
Fact table and dimension table

3) Power Query
Meaning:
Power Query is used to clean, transform, and prepare data before loading it into Power BI.

In simple words:
Raw data is often messy.
Power Query helps to:

remove blank rows
change column names
change data types
split columns
merge tables
filter unnecessary data

Why we use it:
Before making reports, data should be clean. Power Query does that job.

Example:
Suppose an Excel file has:

wrong column names
null values
date in text format
extra spaces

Power Query helps fix all this.

Common tasks in Power Query:

Remove duplicates
Replace null values
Change data type (text to date, text to number)
Merge queries
Append queries
Filter rows
Add custom columns

Shortcut meaning:
👉 Power Query = Data cleaning tool in Power BI

4) DAX
Full form: Data Analysis Expressions
Meaning:
DAX is a formula language in Power BI used to create:

calculations
measures
calculated columns
calculated tables

In simple words:
DAX helps when you want Power BI to calculate something like:

Total Sales
Average Sales
Profit
Sales Growth
Running Total
Year-wise comparison

Example DAX formulas:

Total Sales = SUM(Sales[Amount])
Total Orders = COUNT(Orders[Order_ID])
Average Sales = AVERAGE(Sales[Amount])

Why DAX is important:
Because reports need calculations, and DAX helps create them.

Simple understanding:

Power Query = clean the data before loading
DAX = calculate values after data is loaded

5) Power BI Service
Meaning:
Power BI Service is the online/cloud version of Power BI where we publish and share reports.

In simple words:
After creating a report in Power BI Desktop, we upload it to Power BI Service so others can view it online.

What we can do in Power BI Service:

Publish reports to cloud
Share dashboards with team
Refresh data automatically
Create dashboards
Set alerts
Access reports from browser/mobile

Example:
You create a sales dashboard in Power BI Desktop.
Then you publish it to Power BI Service.
Now your manager can open it online and see the report.

Simple meaning:
👉 Power BI Desktop = Create reports
👉 Power BI Service = Publish, share, and manage reports online

## Key Learning
Today I understood the basic purpose of Power BI and its main components.

## Practice Done
- Installed Power BI Desktop
- Explored Report View, Data View, and Model View
