# MavenTech CRM Sales Opportunities Analysis

## Project Overview :-
The MavenTech CRM Sales Opportunities Analysis project focuses on developing an interactive Power BI dashboard to provide clear visibility into sales performance for MavenTech, a company specializing in selling computer hardware to large businesses. The project aims to transform raw CRM data into actionable insights, enabling sales managers to track their teams' performance, identify trends, and make data-driven decisions.

## Project Goals:-
- Centralized Data Visibility: Integrate data from MavenTech’s CRM system into a single interactive dashboard, making key metrics and insights easily accessible.
- Track Sales Team Performance: Analyze metrics like total sales, win rates, deal closure time, and average sales value across multiple sales teams and agents.
- Identify Sales Trends: Discover quarter-over-quarter trends, identify high-performing products, and analyze sales agent performance.
- Support Strategic Decision-Making: Provide actionable insights to refine pricing strategies, focus on high-potential opportunities, and improve sales efficiency.

## Data Overview:-
- Data Size: The CRM dataset consists of approximately 8K+ rows across four tables—Accounts, Products, Sales Teams, and Sales Pipelines.
- Data Source: Extracted directly from MavenTech's CRM system.
  
## Tables Included:
- Accounts: Contains information on client companies, sectors, revenue, and employee count.
- Products: Includes product names, series, and sales prices
- Sales Teams: Features sales agents, their managers, and their respective regional offices.
- Sales Pipelines: Contains each sales opportunity, including deal stages, engage dates, and close values.

## Data Modifications:-
- Data Cleaning: Removed duplicates, replaced values, and normalized date formats for consistency.
- Data Transformation: Created calculated columns using DAX for metrics, added a Calendar table to support time-based calculations, such as quarter-over-quarter analysis.

## Download Dataset :- 
https://drive.google.com/drive/folders/12wJQinuK-SIywLWYW22ltgNEscM-dBBK?usp=drive_link

## Technologies Used :-
- Power BI: For data integration, modeling, and visualization.
- DAX: Used for creating measures to calculate key metrics like Total Sales, Won Rate (%), Average Weeks to Close, and Quarter-over-Quarter Changes.
- Power Query: For data cleaning and transformation.

## Dashboard Highlights:-
- Interactive Filtering: Allows managers to filter data by team, sector, or time period, with the default view set to Melvin Marxen’s team.
- Dynamic Visuals: Includes bar charts, line graphs, funnel charts, and KPI cards to provide a comprehensive view of sales trends.
- Real-Time Insights: Enables managers to monitor performance metrics and respond quickly to changes, leading to a 30% improvement in decision-making efficiency.
- Customized Slicers: Managers can drill down into specific agents, products, and regions, allowing for granular analysis of team performance.

## Key Insights:-
- Melvin Marxen's team led in terms of total sales, generating $2.25M in revenue. Summer Sewald followed with $2.0M, while lowest sales generated by Dustin Brinkmann's team $1.1M in sales.
- Rocco Neubert led with a 52.07% won rate, followed by Cara Losch at 49.79% and Melvin Marxen have least won rate at 45.72%.
- A higher average sales value indicates that the manager's team is closing higher-value deals. Rocco Neubert's team led in terms of average sales, generating $1.76K. Celia Rouche followed with $1.67K, while lowest average sales generated by Dustin Brinkmann's team $0.92K.
- The top-performing product across all managers was GTX Pro, contributing $110K in sales and achieving a 43.37% win rate. Focus on the promotion of this product could increase overall revenue, as it consistently performs well across sales teams.

## Recommendations:-
- Teams with lower won rates (e.g., Melvin Marxen) should focus on training to improve negotiation and deal closure strategies. Mentoring by top performers like Rocco Neubert could help improve won rates across the board.
- Managers with high % sales discount rates, such as Summer Sewald and Dustin Brinkmann, should review their discounting practices. Implementing a value-based sales strategy could reduce the need for high discounts, improving margins. Introduce a clear discounting policy and provide sales teams with training on value-based selling techniques.
- Since GTX Pro consistently performs well, with high sales and a strong won rate, additional marketing and sales focus on this product could drive even higher revenue. Launch targeted promotional campaigns and incentives for agents to prioritize this product in their sales efforts.

## Learnings:-
- Data Modeling: Enhanced skills in building complex data models, creating relationships between tables, and using DAX for advanced calculations.
- Data Visualization: Gained experience in designing intuitive and interactive dashboards that provide actionable insights.
- Time Intelligence: Developed advanced DAX measures for analyzing quarter-over-quarter performance, won rate changes, and average sales by time periods.

## Challenges:-
- Handling Large Datasets: Managing and transforming data from multiple sources required careful attention to data integrity and relationships.
- Identifying Meaningful Metrics: Understanding which metrics mattered most to MavenTech’s sales managers required deep exploration of the data and collaboration with stakeholders.
