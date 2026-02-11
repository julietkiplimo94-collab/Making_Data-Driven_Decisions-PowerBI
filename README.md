# Making_Data-Driven_Decisions-PowerBI #
Business Intelligence is heavily reliant on data accuracy and integrity. This article will show you how Power Bi is a tool that is easy to use and will help turn your messy data into meaningful insights.
--------------------------------------------------------------------------------------------------------------------------
If you are here, you are probably a data scientist or data engineer, looking for a powerful, easy-to-use business intelligence tool for analysis and visualisation, or a business owner looking to understand your business data and make insightful business decisions.

What are its advantages? How does it give you a cutting edge as a professional in the Big Data industry? 

Well, let me tell you everything I know about this powerful tool!

## <u>Power BI Architecture:<u/> ##

#### Flow of data from a messy raw data flat table to a one-page interactive dashboard. ####

Power BI comes in 4 components that allow you to use it locally or as a service on the cloud. These components are: 
``Power BI Desktop, Power Bi service( Cloud), Power BI Mobile, and Report Server.``

**1. Data Sources:**

Power BI is very popular because of its ability to pull data from numerous sources, making it compatible with most systems that store raw data. These sources include, but are not limited to, Excel, SQL Server, Web applications, etc.)

**2. Data Preparation & Transformation:**

Data transformation is a very important step in data analysis. It is impossible to model or make sense of data that is full of formatting errors, blanks, and duplicates.

- 
***Power Query tool*** is a built-in tool in Power BI that uses the ETL (Extract, Transform, Load) process to clean and transform a big data set before loading it for analysis. 

This process entails removing duplicates, changing incorrect data types, unifying blanks or null values, and trimming extra text characters before loading the data for analysis and visualisation.

**3. Data Modelling:**

- 
***Relationships, Joins and Schemas***

*Relationships* are how Power BI connects tables so that data can flow correctly between them.

Power Bi allows you to easily create and manage relationships between fact and dimension tables. It enables you to arrange cleaned data in schemas that structure the data for analysis, easy update, and retrieval.

*Joins* are used in Power BI to physically combine data from two tables into a single table. They are performed in Power Query during the data preparation stage, before the data is loaded into the Power BI model.

Designing a clear and well-structured model using fact tables, dimension tables, and an appropriate schema is essential for effective and scalable analysis. 

- 
**DAX (Data Analysis Expressions)** is a formula language designed specifically for analytical and business intelligence calculations, such as:
```
totals, averages, percentages, rankings, comparisons.
```
DAX is used to build measures, calculated columns, and calculated tables that help transform raw data into meaningful insights.

**4. Visualization and reporting.**


