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
- **Cumulative Sales**: Visualizes the cumulative sales from the beginning of the transaction year to the last transactional year (2021) and updates dynamically with new data.
- **Top 3 Profitable Customers**: Identifies the three most profitable customers, showcasing their contributions to company growth.

  ![unnamed-12](https://github.com/user-attachments/assets/b7f67f49-69ad-4115-b10c-a761c2041b7a)

- **Top 3 Least Profitable Customers**: Highlights the three least profitable customers, providing insights into potential areas for improvement and customer engagement strategies.
- **Yearly Profit and Growth**: Displays yearly profit figures and growth percentages to track overall financial performance.
- **Monthly Profit Trend**: Analyzes the trend of profits on a monthly basis to identify seasonal patterns and monthly performance fluctuations.
- **Quarterly Profit Trend**: Examines profit trends on a quarterly basis for a broader view of financial performance across the year.
- **Additional Insights**: Includes the number of transactions, total customers, product count, and the number of countries the company sells to.

## Technical Skills
- **DAX (Data Analysis Expressions)**: Utilized for complex calculations and data manipulation within Power BI.
- **Power Pivot**: Used for creating relationships between Fact and Dim Tables, enabling seamless data integration and analysis.
- **Power BI**: Employed for designing the interactive dashboard and visualizing key metrics and trends.

## Soft Skills
- **Analytical Thinking**: Applied analytical skills to interpret data and derive meaningful insights.
- **Attention to Detail**: Ensured accuracy in data handling, calculations, and visualizations.
- **Problem Solving**: Identified and addressed challenges in data integration and dashboard design.
- **Communication**: Effectively communicated findings and insights through a well-structured dashboard.

## Usage
To use this project, download the repository from GitHub and open the Power BI file. Ensure that the dataset is correctly linked to the Fact Table and Dim Tables in Power Pivot. Use the interactive filters for country, products, and months to explore the data dynamically.

