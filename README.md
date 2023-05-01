# ProfitabilityAnalysis_TheEverythingCompany
**This repository contains data analysis of product lines of The Everything Company.**

**Analyse Dataset:** Once we have the dataset our first step is, to know the statements below as a Data Analyst. 

**Problem Statement:** A company’s Head of Finance Mr. Hardik, has requested some metrics on the performance of The Everything Company’s product lines. He has some concerns that there are areas where the company may be losing money. He wants a report with recommendations. Data Set provided by company. 

**Data Story Definition:** Firstly, starting by defining the aims and KPIs for the analysis. These will serve as the foundation for the analysis. After speaking with Hardik, I have come up with the following: 

**Data Story Objectives:** 

        Objective: Review current product lines and find areas for improvement. 

         User: Head of Finance will access the dashboard. 

         Action: Find areas that can improve revenue and low-performing products and regions. 

         Usage Frequency: Monthly (Head of Finance wants to review dashboard monthly).                

**KPIs:** Profit, Quantity and Order Volume. 

**Extract, Transform and Load (ETL):** After defining above all four points, I extracted CSV files in Power BI desktop and transformed them into Power Query. 

Transformation done in file (List of Orders) as below: 

1- Changed Header (using first row as header). 

2- Changed Date type from text (using Locale). 

3-Removed blank rows. 

Transformation done in file Order. Details: 

Changed data type from general to currency in profit column. 

**Data Modeling:** Now, it is time to join the datasets together by performing joins with unique id in “Model” section. To add a new connection, moved the “Order ID” field from “Order Details” to the “Order ID” field in the “List of Orders” table. This will create a connection. Since the “List of Orders” table has unique orders in it and the “Order Details” table has multiple rows for each order, the connection should be “One to Many”. 

**Visualizing the dataset:**  

**Z layout** makes use of the **Gestalt Principle** of having better closure and continuation.  

There are six visuals charts created in this Dashboard. 

KPIs – Used Multi-row cards to visualize Profit, Quantity and No. Of Orders. 

Profit trend chart – Used stacked and column chart to analyze profit Vs. Orders by category. 

Profit by Sub-Category – Used Matrix chart with conditional formatting for lowest and highest subcategory.  

Profitability by Customer- Scatter plot applied to analyze too many data points (no. of customers). 

Profit by State- To find breakdown of the profitability across the different states “Tree Map” chart type. Location-based analysis is a great way to help end users (Head of Finance) to begin to conceptualize where they can make improvements, which usually leads to quicker results. 

Slicer & Filter- To analyze in depth for accurate measures according to date, customer name, by state or by city user can go to slicer and select the date to view profit. 

 

**Additional Insights:** I have added some more insights on another page named “Profit Insights “to make users more interactive with dashboard or report.  

Copied scatterplot from first page “Profit Analysis” and pasted to second page “Profit Insights” and dragged “Sum of Amount” on play axis. While playing the axis the scatter points move as per sub-category changes. 

Key Influencer chart type: This chart type really helps me to understand what is driving the metric that you are interested in. These are also precisely what someone in the role of Head of Finance would be looking for. Besides, this gives your dashboard a major WOW factor and a super cool feature the end users can play with! 

Q&A Chart Type: One of the other very exciting features of Power BI is the Q&A chart. This chart allows users to ask the data questions directly on the dashboard and do their own ad hoc analysis and find out what they are interested in.   

**Results:** I can get answer for the following 

Total profitability seems to have been negative until October 2019. 

Electronic Games and Tables are both negative in terms of profitability and should be looked at. 

182 Customers have a negative profitability out of the 332 (Roughly 55%). 

The customers with negative profitability reside in: Madhya Pradesh & Maharashtra. 

Bookcases and printers seem to be big influencers of the data and are key drivers of overall Revenue (Amount). 

**Recommendations:**

After reviewing the analysis, my recommended course of action. 

Have the Branch Manager review the most unprofitable customers. 

Look at the underperforming States and identify why there is such a large variance between customers’ profitability. 

Consider not selling Tables and Electronic games until costs can be reduced as these are taking away from the profitability of the company. 

Focus on expanding profitable sub-categories to continue trend in profitability. 

 
![Dashboard Visuals]https://github.com/Anupriya-241122/ProfitabilityAnalysis_TheEverythingCompany/blob/main/Screenshot%202023-05-01%20094336.png)

 
