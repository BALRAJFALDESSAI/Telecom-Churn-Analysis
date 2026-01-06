Telecom Churn Analysis: Data-Driven Retention Strategy

Project Overview
This project analyzes a dataset of 243,000+ telecom customers to identify key drivers of churn. Using SQL for data engineering and Tableau for visualization, I developed a "High-Value At-Risk" watchlist and executive dashboards to help reduce customer attrition

Tech Stack
•	Database: MS SQL Server (Data Cleaning & ETL)
•	Visualization: Tableau Public
•	Documentation: Notion & GitHub
•	Language: SQL

Data Cleaning & Transformation (SQL)
To ensure data integrity, I performed several cleaning steps in MS SQL Server:
•	Imputation: Handled negative values in calls_made, sms_sent, and data_used by setting them to 0.
•	Feature Engineering: * Created age_group (18-24, 25-40, etc.) to identify life-stage trends.
o	Segmented customers into income_segment to prioritize high-value retention.
•	View Creation: Created a cleaned view vw_Cleaned_Telecom to serve as the single source of truth for the Tableau export.

Key Insights
•	Churn Rate Stability: The global churn rate is approximately 20%. Surprisingly, churn remains consistent regardless of call volume or data usage.
•	Regional Hotspots: High-churn states were identified using geographic mapping, suggesting localized network or competition issues.
•	High-Value Risk: identified a segment of "High Income" users with declining usage who represent a significant revenue risk.
Strategic Recommendations
1.	Shift Focus from Usage to Quality: Since usage volume doesn't prevent churn, focus on service reliability and network uptime.
2.	Targeted Win-Back Campaigns: Use the "At-Risk" watchlist to trigger automated personalized offers to high-value users before they leave.
3.	Regional Pricing: Conduct competitive benchmarking in the top 5 high-churn states.



