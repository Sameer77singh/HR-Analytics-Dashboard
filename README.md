# HR Analytics Dashboard

## Project Overview
This project is an interactive **HR Analytics Dashboard** built using **Power BI**. The dashboard is designed to analyze human resources data, focusing on employee performance, turnover rates, diversity metrics, and other key HR-related metrics, with visualizations that provide insights into workforce dynamics and HR trends.

## Features
- **Employee Performance Tracking:** Visualize key performance indicators (KPIs) for employees, such as performance ratings, project completion rates, and productivity metrics.
- **Turnover Analysis:** Identify trends in employee turnover, including voluntary and involuntary exits, with demographic breakdowns.
- **Diversity Metrics:** Analyze workforce diversity in terms of gender, age, ethnicity, and other relevant factors.
- **Compensation and Benefits Overview:** Compare compensation packages, including salaries and benefits, across different employee groups.
- **Visualizations:** Utilize line charts, bar charts, pie charts, and heat maps to provide a comprehensive view of HR data.
- **Filter Options:** Allow users to drill down by department, role, tenure, and other categories.

## Technologies Used
- **Power BI:** 
   - Power BI is the main tool used for building and designing the dashboard. Its capabilities for creating interactive visualizations make it ideal for the Prime Video dashboard, allowing users to gain actionable insights from large datasets.
   - Power BI's DAX (Data Analysis Expressions) language is employed to create complex calculations and aggregations, such as calculating rolling averages, growth rates, and custom KPIs.
   - Power BI’s advanced data modeling features enable efficient data transformations, merging different datasets (e.g., viewership, content metadata, and demographic information) to create a unified and comprehensive analysis.

- **Excel/CSV Data:** 
   - Excel or CSV files were used as primary data sources, likely containing viewership data, content performance metrics, user demographics, and other related datasets.
   - These data files were cleaned, transformed, and loaded into Power BI for analysis. Using Excel as a base ensures the data can be easily updated and reloaded for future dashboard iterations.
   - In future expansions, this project can be connected to live data sources or integrated with databases for real-time updates.

- **DAX (Data Analysis Expressions):** 
   - DAX is utilized extensively for calculations and measures within Power BI. Examples include custom time intelligence functions (e.g., year-over-year growth in viewership), content popularity ranking formulas, and metrics for user retention.
   - DAX allows for the creation of dynamic metrics that update based on user interactions, ensuring that visualizations reflect the most relevant and up-to-date data.
   - It helps create powerful aggregations and measures that summarize large amounts of data into digestible KPIs.

- **Data Modeling & Transformation:** 
   - The project involved merging, cleaning, and transforming various datasets (e.g., user engagement data, content metadata) to create a cohesive data model for analysis.
   - Data transformation features in Power BI (Power Query Editor) were used to cleanse and reshape the raw data, handle missing values, create calculated columns, and join tables.
   - The data model was designed to ensure efficient querying and performance, enabling real-time filtering and calculations in the dashboard.
