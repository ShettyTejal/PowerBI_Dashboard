#  Analyzing Ecommerce Sales Data in Power BI

**1. Steps to Analyze Ecommerce Sales Data in Power BI:**
Import your Ecommerce Sales Data into Power BI.
In Power BI Desktop, click on Get Data and choose the relevant source (e.g., Excel or CSV) to import the dataset.

**2. Data Transformation and Cleaning (Power Query)**
If the data is not cleaned you need to clean the Data first by Remove duplicates or irrelevant columns,Fix column names,Handle missing data,Create new columns,Change data types or Merge and Append tables.
You can also use calculated column or measures as i have add column Average order Value(AOV) for Datails table by using Add Calculated Column,AOV = Details[Amount]/Details[Quantity].

**3.Building the Data Model**
You can create relationships between two tables based on common fields (e.g., Order ID from both tables).

**4.Visualizing the Data**
Once the data is ready, you can create interactive visualizations. Some common visualizations for Ecommerce Sales Analysis include:
1.Stacked Column Chart is used to show Profit by Month.
2.Stacked bar Chart is used for Sum of Profit by Sub-Category.
3.Donut Charts are used for Count of PaymentMode by PaymentMode & Sum of quantity by Category 
4.Stacked Bar Chart is used for Sum of amount by of Top 5 states, in this we use filters on visuals to filter top5 states only.
5.Stacked Column Chart is used to find highest purchased customer,in this we use filters on visuals to filter top5 CustomerName only.
6.Used Cards and Slicers also given Title to the dashboard.

**5.Finalizing the Report**
Design: Make sure your report is visually appealing and easy to navigate.
Formatting: Adjust colors, font sizes, and styles to improve readability and user experience.
Dashboard: Arrange the visualizations in a clean layout, ensuring important insights are prioritized and easy to spot.

**Conclusion:**
With Power BI, you can analyze and visualize Ecommerce Sales Data in a highly interactive and insightful way. By following the steps above, you can create a comprehensive dashboard that helps businesses make data-driven decisions regarding sales performance, customer behavior, and product trends.
