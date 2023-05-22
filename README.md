# Sales-Analysis-Using-Excel

![](Sales.jpg)

This is a sales analysis using Microsoft Excel. The data was gotten from quantum analytics and was used to create a dashboard that answers Business related questions asked by stakeholders. The Excel file contains several sheet to different data's.

#Problem Statement 

The aim of this analysis is to answer the following Business related questions

- What month generated the highest revenue?
- In what month did the company make the highest sales? 
- what product generated the highest revenue?
- Who was the highest sales person between 2018 and 2019?
- What region generated the highest revenue?

# Skills & Concept used:

- Index match. This is very similar joins used in SQL to integrate data from various sources together. 
- Data Manipulation & Transformation
- Pivot table
- Pivot chart
- Excel functions

# Data Integration (Index Match)
I was able to merge the various data coming from different sources using the index match function as shown below:

![](Index_Match.jpg)

This was the result as shown below

![](index_match2.jpg)

# Data Manipulation & Transformation

Part of the manipulation I did was to create a column that counts the number of customers. By default, Excel does not have an inbuilt function to a distinct count like in Power Bi using DAX, hence had to use an alternative method. This method entails breaking down the counts into fractions similar to dividing an orange into 4 quarters/fractions and then summing up the 4quarters to get a single whole orange. Below is the the Excel function i used in achieving this

![](Distinct_Count1.jpg)

Below is the end result

![](Distinct_Count2.jpg)

A sum of all the fractions will yield the total number of customers.

# Pivot Table

Pivot Table was used to generate the KPI cards used in the final dashboard to stakeholders.

![](Pivot_Table.jpg)

# Pivot Chart

Similary different pivot charts were created on separate sheets and were then used in the final dashboard sheet.

![](Pivot_Chart.jpg)

# Data Visualization

The visuals used consisted of cards to show different KPI'S, clustered column  & bar chart to show revenue by products & quantity of products sold by sales person, line chart to show sales trend by month & quantity of ggods sold by month, pie chart to show revenue generated by region and slicers by region. The slicers used are to make the dashboard an interactive one so as to answer different business problems based on the data presented. Below is the dashboard

![](Dashboard.jpg)

