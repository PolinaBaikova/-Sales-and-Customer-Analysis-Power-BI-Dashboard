# Sales-and-Customer-Analysis-Power-BI-Dashboard
Analysis of sales, customer behavior, and profitability using Power BI to provide interactive insights into order patterns, shipping costs, and regional performance through comprehensive data visualization.
#Objective
The objective of this project was to analyze sales and customer data from a retail business to gain actionable insights into order patterns, customer loyalty, profitability, and shipping efficiency across different regions and product categories. By integrating multiple data sources and applying various data processing and visualization techniques, the project aimed to provide a comprehensive dashboard that enables stakeholders to explore key performance metrics and support data-driven decision-making.

Data Preparation
The dataset used in this project was sourced from an Excel file containing multiple sheets, including orders, returns, and user information. The data preparation process was carried out in Power BI and involved several key steps to ensure data consistency, accuracy, and usability for analysis.

#Data Consolidation and Cleaning:

Two separate order datasets were combined into a single unified dataset to facilitate comprehensive analysis.
Unnecessary columns were removed to improve data efficiency and relevance.
Column names were standardized to concise and meaningful labels.
Data types were reviewed and corrected to align with analytical requirements.
Data Transformation:

A new product category classification was created by merging relevant columns to provide better grouping and analysis.
An index column was added for record tracking and identification.
Missing values were handled by either replacing them with appropriate values or removing incomplete records to maintain data integrity.
Data Enrichment:

Order records were merged with return data to track returned orders.
Managerial information was incorporated based on regional mappings.
Customer segmentation was applied to categorize customers into key groups such as high-value and repeat customers.
Data Optimization and Filtering:

Duplicate values were identified and resolved across multiple datasets.
A dynamic filtering system using parameters was implemented to allow users to analyze order priorities (Low, Medium, High, Critical).
Data loading optimization techniques were applied by excluding non-essential queries from the data model to improve performance.
Visualizations Created
The final dashboard was designed to be intuitive, interactive, and comprehensive, offering various visualizations to explore sales, profitability, and operational efficiency.

Sales Overview Page:

A hierarchical view of product categories and subcategories was provided to allow users to drill down into specific product lines.
Total sales data was presented in an interactive table, categorized by product and order priorities.
Formatting enhancements such as readable font sizes and data display units were applied to improve clarity.
Conditional formatting was implemented to highlight profitable and non-profitable areas within the sales data.
Shipping Cost Analysis:

A bubble chart was created to visualize the relationship between total sales and average shipping costs across product categories, with profit represented by bubble size. Different colors and shapes were used to distinguish shipping modes.
A bar chart was added to compare average shipping costs across product categories, customer segments, and order priorities, providing users with flexible filtering options.
Trend analysis features were incorporated to observe how shipping costs evolved over time using a date-based animation feature.
Profitability Insights:

A profit matrix was developed to analyze total profit by product categories and shipping methods, providing an overview of profit distribution.
Geographic analysis was conducted using a map visualization that displayed profit distribution across various states, using color gradients to indicate profitability levels.
A dual-axis line and column chart was used to track total profit and average shipping cost trends over time, allowing users to drill down from yearly to monthly views.
Interactive Exploration and Drill-Downs:

Users were provided with dynamic filtering capabilities through slicers, enabling them to explore data by customer segment and product category.
A drill-down feature was implemented to allow users to access more detailed insights by selecting key data points within visual elements.
Tooltip enhancements were applied to provide additional context when hovering over chart elements, offering summary statistics without cluttering the dashboard.
Customized User Experience:

Various elements were strategically positioned and resized to ensure optimal layout and usability.
Advanced interactions were applied to control chart filtering behavior, preventing unnecessary cross-filtering where not needed.
Data quality filters were applied across all pages to exclude records with unspecified order priorities, ensuring a more accurate analysis.
Conclusion
The final dashboard provides a powerful analytical tool for business stakeholders, offering insights into sales performance, customer segmentation, shipping cost efficiency, and overall profitability. The combination of interactive filters, dynamic visualizations, and well-structured data provides users with the ability to explore business operations from various perspectives. By enabling drill-downs, trend analysis, and geospatial insights, the dashboard supports strategic planning and informed decision-making, helping the business optimize its operations and enhance customer engagement.
