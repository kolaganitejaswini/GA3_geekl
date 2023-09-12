KPI Dashboard Project
This project aims to build a comprehensive KPI dashboard for user-generated sessions on a website.

Data Sources:
The data will be collected from Google Analytics 360.

Data Storage:
The data will be stored in BigQuery tables.

Data Processing:
A multi-hop architecture will be used to transform and refine the data. The multi-hop architecture will consist of three stages: bronze, silver, and gold.
The bronze stage will ingest the raw event data into BigQuery and store it as partitioned data.
The silver stage will extract and transform sessions from both the web and app platforms, aggregating the data to provide a holistic view of user activity.
The gold stage will calculate the KPIs based on the refined data.
KPIs
The KPIs will focus on popular pages, user activity, and session duration.

Popular pages: The number of visits to each page, broken down by country and device.
User activity: The number of pageviews, hits, and events per session, broken down by day and hour.
Session duration: The length of each session, broken down by high, medium, and low ranges.
Visualization
The data will be visualized using Looker Studio. Looker Studio is a powerful data visualization and reporting tool that allows users to create intuitive and interactive dashboards.

Automation:
Cloud Composer will be used to automate the data processing tasks. Cloud Composer is a managed workflow orchestration service that can be used to schedule and run complex data pipelines.

Next Steps:
The next steps for this project are to:
Implement the data pipeline in Cloud Composer.
Build the KPI dashboard in Looker Studio.
Collect feedback from stakeholders and make improvements to the dashboard.
