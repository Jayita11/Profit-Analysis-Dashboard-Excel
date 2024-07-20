# Profit Analysis Dashboard

## Project Overview
This dynamic and highly intuitive DAX-based eCommerce dashboard offers a real-time snapshot of the financial position of a business and facilitates future planning by highlighting metrics that directly impact the business's bottom line. When used as part of good business practices in a Financial Planning & Analysis (FP&A) department, financial dashboards improve executives' ability to always keep an eye on essential KPIs. This reduces the chances that important decisions are delayed because executives don’t have easy, self-service insight into performance. The dashboard is built to handle large datasets and provide insightful analytics for sales data spanning from 2019 to 2021, with a primary objective to facilitate better business decisions by visualizing key performance indicators such as cumulative sales, profitable customers, and profit trends.

## Dataset Used
The dataset used in this project is stored in a folder and comprises transaction details from 2019 to 2021. The data includes important information such as purchases, quantity, order dates, and identifiers that link to dimensional tables (Dim Tables). These Dim Tables contain data on customers, products, and other relevant dimensions, enabling comprehensive analysis through relationships created in Power Pivot.

## Key Steps in the Project
1. **Data Extraction and Transformation**: Utilized Power Query to extract and transform the data from the source files. The transformed data was then transferred to Power Pivot for further analysis.
2. **DAX Calculations**: Leveraged DAX to define custom calculations in Power Pivot. This included using functions like `RELATED`, `SUMX`, and `SUM` to generate reports on customer analysis and year-to-date profit trends.
3. **KPI Calculation**: Implemented functions such as `DISTINCTCOUNT`, `COUNTROWS`, and `IF` to calculate the number of customers over time, the total number of transactions, and other key performance indicators (KPIs).
4. **Automation**: Automated the removal of manual filters using macros and VBA to streamline the data analysis process.
5. **Dashboard Creation**: Designed an interactive dashboard using Power BI with filters for country, products, and months to enable dynamic data analysis.

## Dashboard Components
- **Cumulative Profit**: Visualizes the cumulative profit from the beginning of the transaction year to the last transactional year (2021) and updates dynamically with new data.

  ![unnamed-17](https://github.com/user-attachments/assets/0466d019-5729-484c-b795-b1fe7cc9accd)

- **Top 3 Profitable Customers**: Identifies the three most profitable customers, showcasing their contributions to company growth.

  ![unnamed-12](https://github.com/user-attachments/assets/b7f67f49-69ad-4115-b10c-a761c2041b7a)

- **Top 3 Least Profitable Customers**: Highlights the three least profitable customers, providing insights into potential areas for improvement and customer engagement strategies.

  ![unnamed-15](https://github.com/user-attachments/assets/cd0cdf7f-32ce-49de-a7c1-1326819380c6)

- **Yearly Profit and Growth**: Displays yearly profit figures and growth percentages to track overall financial performance.

  ![unnamed-16](https://github.com/user-attachments/assets/d106d0e2-c4a2-477a-9261-db61a13922f7)

- **Monthly Profit Trend**: Analyzes the trend of profits on a monthly basis to identify seasonal patterns and monthly performance fluctuations.

  ![unnamed-13](https://github.com/user-attachments/assets/70f563e8-077c-40e2-a06e-326edce00c7a)

- **Quarterly Profit Trend**: Examines profit trends on a quarterly basis for a broader view of financial performance across the year.

  ![unnamed-14](https://github.com/user-attachments/assets/91bea56c-6ce6-479e-ab9a-3a9454a39816)

- **Active Filters**: Includes interactive filters for country, products, and months. These filters allow users to quickly select options to consolidate data for one or multiple regions and adjust the analysis period. This enhances the dashboard's interactivity and flexibility.

  ![unnamed-20](https://github.com/user-attachments/assets/e08dc72e-5f34-4dcb-9c92-f8be12768232)
  
  ![unnamed-21](https://github.com/user-attachments/assets/afd4d32d-c4e8-435a-990f-58fee9566e22)

  ![unnamed-22](https://github.com/user-attachments/assets/26e96acd-e198-43c6-9e55-17e1ce4fc93f)



- **Additional Insights**: Visualizing critical KPIs with easy-to-read cards for smart and rapid decision-making, such as the number of transactions, total customers, current items, COGS, revenue, profit, quantity sold, and regions the company sells to.

  ![unnamed-18](https://github.com/user-attachments/assets/2b82bb59-7ee9-4611-b32f-2006b7e26ffd)
  
  ![unnamed-19](https://github.com/user-attachments/assets/6c4f2919-fdc3-4742-841f-454d406875b1)

## Dashboard Overview
 ![unnamed-23](https://github.com/user-attachments/assets/6bf44b5e-a859-45db-b96a-66e314843a1f)
 
 ![Animation1-2](https://github.com/user-attachments/assets/34a9811f-cbb1-4587-a3d3-44d97c84a94b)
 
 ![Animation2-2](https://github.com/user-attachments/assets/8acf1eeb-1488-422d-b00b-a115a7ba817b)
 
 ![Animation3](https://github.com/user-attachments/assets/ab1019a9-1956-44f2-8080-717fb17f84ae)

## Technical Skills
- **DAX (Data Analysis Expressions)**: Utilized for complex calculations and data manipulation within Excel.
- **Power Query**: Used for extracting and transforming data before analysis.
- **Power Pivot**: Used for creating relationships between Fact and Dim Tables, enabling seamless data integration and analysis.
- **Excel**: Employed for designing the interactive dashboard and visualizing key metrics and trends.
- **VBA and Macros**: Automated manual processes to improve efficiency.

## Soft Skills
- **Analytical Thinking**: Applied analytical skills to interpret data and derive meaningful insights.
- **Attention to Detail**: Ensured accuracy in data handling, calculations, and visualizations.
- **Problem Solving**: Identified and addressed challenges in data integration and dashboard design.
- **Communication**: Effectively communicated findings and insights through a well-structured dashboard.


