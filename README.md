# Sales-and-Customer-Analysis-Power-BI-Dashboard
Analysis of sales, customer behavior, and profitability using Power BI to provide interactive insights into order patterns, shipping costs, and regional performance through comprehensive data visualization.
# Objective
The objective of this project was to analyze sales and customer data from a retail business to gain actionable insights into order patterns, customer loyalty, profitability, and shipping efficiency across different regions and product categories. By applying various data processing and visualization techniques, the project aimed to provide a comprehensive dashboard that enables stakeholders to explore key performance metrics and support data-driven decision-making.

# Data Preparation and Transformation
The dataset used in this project was sourced from an Excel file containing multiple sheets, including orders, returns, and user information. The data preparation process was carried out in Power Query Editor and involved several key steps to ensure data consistency, accuracy, and usability for analysis. This phase involved consolidating multiple order records into a single dataset, removing redundant and irrelevant fields to streamline the dataset and improve performance, standardizing categorical values and dealing with missing values by either replacing them with appropriate values or removing incomplete records. 

Data aggregation techniques were employed to summarize business performance at various levels. The dataset was grouped by region and customer segment to calculate key performance indicators such as the number of orders, total profit, and average profit per order. Customer segmentation was applied to categorize customers into key groups such as high-value and repeat customers. A dynamic filtering system using parameters was implemented to allow users to analyze order priorities (Low, Medium, High, Critical). 

# Visualization
Data loading optimization techniques were applied by excluding non-essential queries from the data model and the next step involved structuring the information in a way that made it easier to explore and interpret. To achieve this, grouping of shipping modes was created to categorize shipments as either Air or Ground, providing a higher-level overview of logistics. Additionally, a hierarchy was built from product categories and subcategories to facilitate drill-down analysis.

A table visualization was then created to present total sales for different product categories and subcategories. Conditional formatting was introduced to the Sales column to highlight positive and negative profit trends using color coding.

Next dashboard page called Shipping Costfeatures a bubble chart to visualize the relationship between total sales and average shipping costs across product categories and shipment modes, with profit represented by bubble size. The chart was enhanced with differentiated colors and shapes for various shipping modes, and animations were added to observe trends over time. A horizontal bar chart allows users to analyze average shipping costs across product categories, customer segments, or order priorities, providing an interactive experience through parameter-driven filtering.

A Profit dashboard page provids a view of profitability across different dimensions. A matrix visualization was created to showcase total profits by product category and shipment mode, sorted in descending order to highlight key revenue drivers. The matrix allowed users to expand and drill down through hierarchical levels for more granular insights. A geographic map visualization was introduced to display total profit distribution across states, utilizing color gradients to depict variations in profitability. Additionally, a dual-axis line and column chart was added to track total profit and average shipping costs over time, enabling users to drill down from years to months.

To further enhance interactivity, additional pages such as Tooltip and Drillthrough were implemented. The Tooltip page featured a column chart displaying average shipping costs by product sub-category, which could be accessed by hovering over visual elements in other pages. The Drillthrough page enabled users to click on specific product categories and navigate to a dedicated view displaying detailed cost breakdowns and key metrics. Filters were applied across all pages to exclude records with unspecified order priorities, ensuring cleaner and more accurate analysis.

The final dashboard provides a comprehensive, interactive interface for analyzing sales, customer behavior, and profitability trends across multiple dimensions. Users can explore insights by interacting with visual elements, applying filters, and utilizing drill-through capabilities to dive deeper into key performance metrics. The project effectively transforms raw business data into actionable insights, supporting data-driven decision-making and strategic planning for the retail business.

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
