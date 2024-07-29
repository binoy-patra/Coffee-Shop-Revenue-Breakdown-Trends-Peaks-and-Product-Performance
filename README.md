# Coffee Shop Revenue Breakdown: Trends, Peaks, and Product Performance

## Overview:
This Power BI dashboard project aims to analyze sales performance across three coffee shop locations over a six-month period. The dashboard is designed to address key business challenges and provide actionable insights to optimize operations and enhance revenue generation. ☕

## Business Problem:
The coffee shop chain faces challenges in understanding sales trends, peak hours, and product performance across different locations. This lack of clarity hampers effective staff scheduling, inventory management, and marketing strategies. The primary business problem is to identify trends, peak periods, and product preferences to drive better decision-making and improve overall performance.

## Methodology:
- **Data Collection:** Sales data was collected for three coffee shop locations from January to June. The data includes transactions, sales amounts, product categories, and time stamps.
- **Data Transformation:** Utilized Power BI to perform data transformations, including extracting month names, day names, and hours from timestamps.
- **Visualization:** Created various visualizations such as total sales month-wise, peak hours of sales, sales variation, and breakdowns by store location and product category.
- **Analysis Tools:** Employed heat maps and a decomposition tree to analyze revenue, order quantities, and performance metrics in a detailed manner.

## Dataset Overview:
- **Time Frame:** January to June
- **Locations:** Three coffee shop locations 
- **Dataset Provider:** Maven Analytics
- **Data Points:**
  - `transaction_id`: Unique identifier for each transaction.
  - `transaction_date`: Date when the transaction occurred.
  - `transaction_time`: Time when the transaction occurred.
  - `store_id`: Identifier for the store where the transaction took place.
  - `store_location`: Geographical location of the store.
  - `product_id`: Unique identifier for the product sold.
  - `transaction_qty`: Quantity of the product sold in the transaction.
  - `unit_price`: Price per unit of the product.
  - `product_category`: Category to which the product belongs (e.g., coffee, tea, bakery).
  - `product_type`: Type of product (e.g., espresso, latte).
  - `product_detail`: Detailed description of the product.
  - `Size`: Size of the product (e.g., small, medium, large).
- **Calculated/Created Data Points:**
  - `Total_bill`: Total amount billed for the transaction.
  - `Month Name`: Name of the month when the transaction occurred.
  - `Day Name`: Name of the day when the transaction occurred.
  - `Hour`: Hour of the day when the transaction occurred.
  - `Day of Week`: Day of the week when the transaction occurred.
  - `Month`: Numeric representation of the month when the transaction occurred.

**Explore the interactive dashboard and filter based on your needs to gain tailored insights into sales performance. 😊**                  

Here is Excel Dashbord View: ![Excel Dashboard](https://github.com/binoy-patra/Coffee-Shop-Revenue-Breakdown-Trends-Peaks-and-Product-Performance/blob/main/Images/Coffee%20Shop%20Sales%20Excel%20Dashboard.png)

Here is Power BI Dashboard Link:** [Power BI Dashboard](Maven Analytics](https://mavenanalytics.io/project/17801) 

## Key Insights and Findings:
- **Revenue Trends:** Monthly sales data shows a steady increase from February, with June recording the highest revenue across all locations.
- **Peak Hours:** The busiest hours are from 6 am to 10 am for Hell's Kitchen and Lower Manhattan, while Astoria's peak hours are from 7 am to 10 am. These insights help in optimizing staff schedules.
- **Sales Variation:** Significant sales variations are observed on weekdays, with Hell's Kitchen experiencing peak transactions on Fridays and Tuesdays, while Astoria’s busiest days are Thursdays and Mondays.
- **Product Performance:**
  - **Coffee:** Contributes 39% to total revenue, with Astoria leading in coffee sales, particularly in gourmet brewed coffee.
  - **Tea:** Contributes 28% to total revenue, with Astoria outperforming in tea transactions, particularly in brewed chai tea.
  - **Bakery:** Contributes 12% to total revenue, with Lower Manhattan leading in bakery sales.
- **Store Performance:** Lower Manhattan, while having the lowest total revenue, generates the highest revenue during peak hours. Astoria excels during non-peak hours despite shorter operational hours.
- **Heat Maps and Decomposition Tree:** Heat maps reveal revenue and order quantities across different times, while the decomposition tree provides a breakdown by product category and store location, highlighting areas for potential growth and improvement.

## Conclusion:
The Power BI dashboard project has provided a comprehensive analysis of coffee shop sales across three locations over six months. The data reveals clear patterns in sales trends, peak hours, and product performance. Key findings indicate that while revenue generally increases over time, there are distinct peak periods and variations in sales performance across different locations. Astoria excels in tea sales and non-peak hours, Hell's Kitchen shows high transaction volumes during specific weekdays, and Lower Manhattan performs exceptionally well during peak hours.

## Recommendations:
- **Optimize Staffing and Scheduling:**
  - **Peak Hours:** Adjust staff schedules to match the peak hours identified (6 am - 10 am for Hell's Kitchen and Lower Manhattan, 7 am - 10 am for Astoria). This will ensure adequate staffing during high-traffic periods and improve service efficiency.
- **Targeted Marketing Strategies:**
  - **Product Promotion:** Focus on promoting the top-selling products such as gourmet brewed coffee and brewed chai tea in locations where they perform best. Consider targeted promotions and discounts to boost sales in less popular product categories.
- **Inventory Management:**
  - **Stock Levels:** Align inventory levels with sales trends and peak hours. Ensure higher stock availability of popular items during busy periods and reduce stock for less popular items.
- **Operational Hours Review:**
  - **Extended Hours:** Given that Lower Manhattan generates significant revenue during peak hours, consider extending operational hours to capture additional sales potential.
- **Location-Specific Strategies:**
  - **Store Performance:** Develop tailored strategies for each store based on their unique sales performance. For instance, invest in improving coffee and tea offerings in Astoria and enhance bakery promotions in Lower Manhattan.
- **Data-Driven Decisions:**
  - **Continual Analysis:** Regularly update the dashboard with new data to track performance trends and adjust strategies accordingly. Utilize insights from heat maps and decomposition trees to drive continuous improvements.
- **Customer Insights:**
  - **Feedback Collection:** Implement mechanisms to gather customer feedback to better understand preferences and improve product offerings based on real-time customer data.

By implementing these recommendations, the coffee shop chain can enhance its operational efficiency, optimize revenue generation, and improve overall business performance.

For further inquiries, contact me at [binoypatra@gmail.com](mailto:binoypatra@gmail.com) or reach out on LinkedIn: [Binoy Patra](https://www.linkedin.com/in/binoy-patra-b9277b1b2).
