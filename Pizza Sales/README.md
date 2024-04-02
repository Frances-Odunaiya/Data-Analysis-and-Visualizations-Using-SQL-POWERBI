# PIZZA SALES DASHBOARD REPORT PROJECT WITH SQL AND POWER BI

## Introduction
The Pizza Sales Dashboard Project aims to analyze pizza sales data using SQL queries and visualize the insights through an interactive dashboard created with Power BI. By combining SQL for data analysis and Power BI for visualization, this project provides a comprehensive solution for understanding and presenting pizza sales trends, customer preferences, and revenue metrics.

<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20150307.png" alt = "Home">
[Here](https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/PIZZA%20SALES%20SQL%20QUERIES%20-%20Report.docx) is the link to the SQL Queries used to generate the report.

## Problem Statement

*KPI Requirement*

We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:
1. Total Revenue: The sum of the total price of all pizza orders.
2. Average Order Value: The average amount spent per order, calculated by dividing the total revenue by the total number of orders.
3. Total Pizzas Sold: The sum of the quantities of all pizzas sold.
4. Total Orders: The total number of orders placed.
5. Average Pizzas Per Order: The average number of pizzas sold per order, calculated by dividina the total number of pizzas sold by the total number of orders.
   
*Charts Requirement*

4. Percentage of Sales by Pizza Size: This chart will help us understand customer preferences for pizza sizes and their impact on sales.
5. Total Pizzas Sold by Pizza Category: This chart will allow us to compare the sales performance of different pizza categories.
6.Top 5 Best Sellers by Revenue, Total Quantity and Total Orders: This chart will help us identity the most popular pizza options.
7. Bottom 5 Best Sellers by Revenue, Total Quantity and Total Orders: This chart will enable us to identify underperforming or less popular pizza options.

## Features

- Data Extraction with SQL: Utilize SQL queries to extract data from the pizza sales database.
- Data Cleansing and Transformation: Clean and transform the extracted data to prepare it for analysis.
- Descriptive Analytics: Perform descriptive analysis using SQL to calculate key metrics such as total sales, average order value, top-selling pizza flavors, etc.
- Visualization with Power BI: Create visually appealing and interactive dashboards in Power BI to represent the analyzed data.
- Time Series Analysis: Analyze sales trends over time to identify patterns and seasonality.
- Dynamic Filters and Interactivity: Implement dynamic filters and interactive elements in the Power BI dashboard for user exploration.

## Tools and Technologies

- Azure Data Studio: For querying and managing the pizza sales database.
- Power BI Desktop: To create interactive dashboards and reports.
- SQL: Used for data extraction, transformation, and analysis.
- Power Query (M Language): For data cleansing and transformation within Power BI.
- DAX (Data Analysis Expressions): Used for creating calculated columns and measures in Power BI.

## Project Workflow

- Data Extraction: Write SQL queries to extract relevant data from the pizza sales database.
- Data Cleansing and Transformation: Clean and transform the extracted data using SQL queries or Power Query in Power BI.
- Visualization Development: Create visualizations in Power BI using various chart types (e.g., bar charts, line charts) to represent the analyzed data.
- Dashboard Design: Design an interactive dashboard layout in Power BI, incorporating the created visualizations and enabling interactivity.
- Dynamic Filters and Interactivity: Implement dynamic filters, slicers, and drill-down functionalities to enhance user interactivity.
- Time Series Analysis: Add time series charts to the dashboard to visualize sales distribution and trends.
- Documentation and Presentation: Document the analysis process, dashboard functionalities, and insights derived from the data. Prepare a presentation to share the findings with stakeholders.

## Key Findings

- **Key Performance Indicators**: Looking at the Total Revenue, Avg Order Value, Total Pizzas sold, Total Orders, and Avg Pizzas per Order provides us with valuable insights into the performance of various KPIs, enabling data-driven decision-making and strategic planning.
<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20221321.png" alt = "KPI">

- **Busiest Days and Times**: Understanding these busiest days and times enables effective staffing, inventory management, and marketing strategies to capitalize on peak sales periods.In this analysis, i found that orders are highest on Friday. Also for the monthly pattern, I noticed that the maximum orders took place in July.
<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20221419.png" alt = "Busy days and times">

- **Sales Performance**: Comprehending sales performance metrics enables informed decision-making, strategic planning, and the refinement of sales strategies, contributing to business growth and profitability. In this analysis, Classic Category contributes to maximum sales and total orders while the Large size pizza contributes to maximum sales.
<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20221436.png" alt = "Sales Performance">

- **Best Sellers**: Recognizing top sellers will enable this Pizza Company to leverage its popular products, enhance marketing strategies, and increase profitability. For revenue, The Thai Chicken pizza contributes to maximum Revenue. For Quantity, The Classic Deluxe Pizza contributes to maximum Total Quantities. For Total Orders, The Classic Deluxe Pizza contributes to maximum Total Orders.
<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20221517.png" alt = "Best Sellers">

- **Worst Sellers**: Recognizing underperforming products enables this pizza company to evaluate market demand, enhance product offerings, and streamline inventory management strategies. The Brie Carrie Pizza contributes to minimum Revenue, Quantity, and Total Orders respectively.
<img src = "https://github.com/Frances-Odunaiya/Data-Analysis-and-Visualizations-Using-SQL-POWERBI/blob/main/Pizza%20Sales/Pizza%20Sales%20Images/Key_Findings_on_Visualizations/Screenshot%202024-04-01%20221533.png" alt = "Worst Sellers">

## Recommendations

- To effectively manage busiest days and times, businesses can implement several key strategies. Firstly, staffing levels should be adjusted to accommodate peak periods, ensuring sufficient personnel to provide prompt service and minimize customer wait times. Adequate inventory levels of popular items should be maintained to prevent stockouts and meet increased demand during busy hours. Offering promotions or specials during slower periods can incentivize customers to visit during off-peak times, helping to distribute customer traffic more evenly throughout the day. Implementing reservation systems and encouraging online ordering can streamline the ordering process and reduce congestion in-store. Leveraging customer engagement initiatives and analyzing customer behavior data allows for targeted marketing efforts and personalized promotions to drive sales during slower periods. Additionally, adjusting operating hours based on customer traffic patterns and demand trends optimizes resource allocation and maximizes profitability. Continuously monitoring customer traffic patterns and feedback enables businesses to identify areas for improvement and adapt strategies accordingly, ultimately enhancing the overall management of busiest days and times.
  
- To enhance sales performance, businesses should focus on several key strategies. Firstly, providing comprehensive sales training programs can equip sales teams with the necessary skills and knowledge to effectively communicate with customers and close deals. Targeted marketing campaigns aimed at specific customer segments can increase brand visibility and attract potential buyers. Implementing a customer relationship management (CRM) system enables better management of leads and personalized communication, leading to improved customer retention. Additionally, incentive programs such as sales commissions and rewards can motivate sales staff to achieve their targets. By establishing clear sales pipelines, prioritizing high-potential opportunities, and encouraging cross-selling and upselling, businesses can maximize sales opportunities. Regularly reviewing performance metrics, integrating customer feedback, and providing sales enablement tools further contribute to improving sales performance. Overall, fostering a culture of continuous improvement and learning helps businesses adapt to changing market dynamics and drive sustained sales growth.

- To optimize the performance of top-selling products, businesses should focus on expanding into new markets and diversifying product lines to cater to evolving customer needs. Continuous monitoring and adjustment of pricing strategies are essential to ensure competitiveness while maximizing profitability. Investing in brand promotion and customer engagement initiatives strengthens brand loyalty and reinforces the popularity of top-selling products. Upholding high-quality standards and streamlining supply chain processes ensures consistent availability and customer satisfaction. Ongoing competitive analysis and integration of customer feedback guide product innovation and differentiation, while embracing sustainable practices enhances brand reputation and appeal. By implementing these strategies, businesses can sustain the success of top-selling products, drive growth, and maintain a competitive edge in the market.

- To address low-performing products, businesses should conduct comprehensive market research to identify market gaps and customer preferences. Utilizing customer feedback, product improvements can be made to better align with customer needs. Pricing strategies should be reviewed and adjusted to enhance competitiveness without compromising profitability. Targeted marketing campaigns can increase product visibility, while bundle offers and cross-selling techniques can stimulate sales. Optimal inventory management practices should be implemented to minimize excess inventory. Additionally, repositioning products within the market and exploring new distribution channels or partnerships can open up new sales opportunities. Continuous monitoring of sales performance and customer feedback allows for ongoing adjustments to strategies. By implementing these recommendations, businesses can rejuvenate sales and improve the overall performance of low-performing products.

## Conclusion

In conclusion, optimizing business performance requires a holistic approach that addresses various aspects of operations. For low-performing products, businesses should focus on market research, product improvement, and targeted marketing to revitalize sales and align offerings with customer needs. Enhancing sales performance involves training, marketing, and customer relationship management to drive revenue growth and improve customer satisfaction. Managing busiest days and times requires effective staffing, inventory management, and customer engagement strategies to ensure smooth operations and maximize sales opportunities. Finally, identifying and leveraging best-performing products linked to high revenue entails continuous monitoring, product diversification, and pricing optimization to capitalize on successful offerings and sustain business growth. By addressing these key areas comprehensively, businesses can achieve optimal performance and drive long-term success in competitive markets.

The Pizza Sales Dashboard Project with SQL and Power BI provides a powerful platform for analyzing and visualizing pizza sales data. By leveraging SQL for data analysis and Power BI for visualization, this project enables stakeholders to gain actionable insights, make informed decisions, and optimize business strategies based on the analyzed data.

## Repository Structure

- Pizza Sales/Pizza Sales Images/: Contains the images used in this project.
- Pizza Sales/PIZZA SALES SQL QUERIES - Report: SQL scripts for data extraction, analysis, and transformation.
- Pizza Sales/Pizza Sales Report Dashboard: Power BI report files (.pbix) containing the interactive dashboards.
- Pizza Sales/pizza_sales_excel_file: Contains the pizza sales database or dataset.

## Contributions

Contributions to this project are welcome! If you have suggestions, enhancements, or want to report issues, feel free to open an issue or submit a pull request.

## Thank you for stopping by!
