# MS Excel_Portfolio / Project: Production Data Analysis #

![Dashboard](/Images/Dashboard.jpg)

## Introduction ##

This analytics project was performed for a **Production Manager or  Plant Head of a Fictional Manufacturing Industry**. It focuses on analyzing production floor data from a Manufacturing Industry to **uncover actionable insights about production performance, production plan, and production optimization**. The goal is to demonstrate how raw production or manufacturing data can be transformed into meaningful information to support data-driven strategic decisions in industrial context.

By using Excel, I have uncovered key metrices, performed various analysis, and designed an interactive dashboard. Overall, the analysis provides following insights :

1. 📈 **Key Metrices** – Total No. of Orders, Total Planned Quantity, Actual 
Produced Quantity, Average Production Efficiency, Average Lead Time, Total Production Cost etc.
2. 🏭 **Production Insights** – Planned vs Actual Production by Plants and Shifts, Average Production Efficiency by Plants and Shifts, Average Lead Time by Plants and Shifts.
3. 👥 **Order Analysis** – Products with Highest Order Volume, Monthly Trend of Order Volume, Distribution of Orders across Plants and Shifts, and current status of orders placed. 
4. 💰 **Cost Analysis** – Total Production Cost by Plants and Shifts, Average Unit Production Cost by Plants and Shifts, Monthly Trend of Total Production Cost, Monthly Trend of Average Unit Production Cost, Top 5 Products in terms of Total Production Cost, Top 5 Products in terms of Average Unit Production Cost.


## 🛠️ Skills Demonstrated ##

This project demonstrates the end-to-end Excel Data Analysis workflow, covering data preparation, analysis, and dashboarding.

🔄 **Data Preparation / Cleaning**

- 📥 Extracted raw data from the web and transformed to Excel format.

- 🧹 Cleaned and transformed data: removed unnecessary columns, handled blanks/errors, ensured correct data types.

- 🔑 Looked for duplicates, but did not find one.


📊 **Data Analysis**

- ➕ **Calculated Columns**: We have added and calculated several additional column to the data table to find out the important  information like Efficiency, Lead Time, Production Variance, Target Met? etc. We have applied several Formulas like Subtraction, Division, IF, IFS to calculate those columns. 

- ⏳ **Conditional Formatting**: We have also applied Conditional Formatting to highlight Over Production, Under Production, Target Met as well as orders that need attention. 

![Calculated Columns and Conditional Formatting](/Images/Conditional%20Formatting.jpg)

- 🧮 **Formulas and Functions**: To find out the key metrices and statistics, we have also applied various functions. The functions we used are Sum, SumIF, SumIFs, Average, AverageIF, AverageIFs, Min, Max, MinIFs, MaxIFs, IF, IFS, Sort, Unique, Text, Date, Nesting Function etc.

![SumIF Function](/Images/SumIF.jpg)
![SumIFs Function](/Images/SumIFs.jpg)
![AverageIFs Function](/Images/AverageIFs.jpg)
![Nesting Function for Median](/Images/MedianIF.jpg)
![Nesting Function for Unique](/Images/Unique.jpg)

- 📈 **Pivot Table and Pivot Chart**: To design a dynamic Dashboard, we have created several pivot tables and pivot charts. They have given us the same output as "Formulas & Functions", but they are much more convenient and dynamic. we have also given each pivot table a logical name and customized the pivot tables and charts as needed. We have also added slicer, timeline, filter connection to make the analysis more dynamic.

![Order Analysis by Pivot Table](/Images/Order%20Analysis_pivot.jpg)

![Production Analysis by Pivot Table](/Images/Production_Pivot.jpg)

![Cost Analysis by Pivot Table](/Images/Cost_Analytics_pivot.jpg)


📈 **Data Visualization**

Data visualization is an important part of a Data Analytics Project. It highlights how we read, understand, and interpret our data. When to use which chart and for what type of data is very crucial to know. Here I shall demonstrate what type of charts we used and why:

- 📉 **Line Charts** → To show a trends over time (Year-over-Year, Month-over-Month, Quater-over-Quater). We used it to show Monthly Trend of Order Volume, Monthly Trend of Total Production Cost, Monthly Trend of Average Unit Production Cost.

- 🗂️ **Cards** → To demonstrate Key KPIs. We used it to show Total No. of Orders, Total Planned Quantity, Actual Produced Quantity, Average Production Efficiency, Average Lead Time, Total Production Cost etc.

- 📊 **Bar/Column/Cluster Column/Stacked Bar Charts** → To compare categorical data or item. We used it to show Products with Highest Order Volume, Planned vs Actual Production by Plants and Shifts, Average Production Efficiency by Plant and Shifts, Top 5 Products in terms of Total Production Cost, Top 5 Products in terms of Average Unit Production Cost etc.

- 🥧 **Pie Chart** → To exhibit composition or part-to-whole relationship (most cases in terms of percentage). We used it to show the Current Status of Orders Placed, means which percentage of orders processed and not processed.

🎛️ **Interactive Dashboard**

- 🎨 Delivered a business-friendly, interactive Excel dashboard that enables management to monitor performance, track production efficiency, and support strategic decision-making.

## Conclusion

The Production Analytics Dashboard demonstrates how raw manufacturing data can be transformed into actionable business insights using Excel. Through structured data preparation, analysis, and interactive visualization, this project delivers a 360° view of orders, production, and cost — empowering managers to make informed, data-driven decisions.

This project highlights my ability to perform comprehensive data analysis in Excel, create visually engaging dashboards, and generate meaningful insights for operational optimization..

Since this project involved a single, relatively small dataset, I focused on core Excel analysis features without using Power Query, Power Pivot, or DAX. However, I plan to apply these advanced tools in my next project to demonstrate data modeling, relationships, and more scalable analytics workflows.

📚 **Key Takeaways from this project**

- Gained hands-on experience in end-to-end Excel data analytics, covering data cleaning, transformation, analysis, and dashboard creation.

- Strengthened understanding of manufacturing and production performance metrics such as efficiency, lead time, variance, and cost optimization.

- Enhanced proficiency with advanced Excel functions (SUMIFS, AVERAGEIFS, IF, IFS, nested functions) to perform complex calculations and derive insights.

- Improved ability to design interactive dashboards using PivotTables, PivotCharts, Slicers, and Timelines for dynamic, user-friendly analysis.

- Learned how to choose and apply the right visualization types (line, bar, pie, combo, card) to communicate insights effectively.

- Developed stronger data storytelling and business insight skills — transforming raw production data into actionable information for decision-making.

- Understood the limitations of Excel in professional analytics projects:

    - While Excel is powerful for data analysis and quick insights, it is less efficient for complex or large-scale dashboard design.

    - Creating visually appealing dashboards requires manual formatting and significant effort compared to specialized BI tools like Power BI or Tableau.

    - Managing data updates and scalability can become challenging when dealing with large or frequently changing datasets.