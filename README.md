1. Project Title

HealthCare Claims and Insurance Intelligence Dashboard | Power BI Project

2. Purpose

This project presents an interactive Power BI dashboard designed to analyze healthcare claims data, insurance payouts, provider performance, and member demographics.

The dashboard enables healthcare administrators, insurance analysts, and finance teams to monitor claim trends, optimize costs, evaluate provider efficiency, and make data-driven strategic decisions.

3. Tech Stack

📊 Power BI
🧮 DAX (Data Analysis Expressions)
🔄 Power Query (ETL & Data Transformation)
🗂️ Data Modeling (Star Schema)
📁 Dataset used – Healthcare Claims Dataset (Dataset from Maven Analytics)

4. Data Source

Healthcare Claims dataset used for insurance and claims analytics (Maven Analytics dataset).

5. Features
5.1 Business Problem

Healthcare organizations and insurance providers face challenges such as:

Limited visibility into claim cost distribution

Difficulty identifying high-cost age groups

Poor tracking of insurance vs patient payment contribution

Lack of provider performance benchmarking

Limited insight into disease and treatment patterns

These issues can lead to rising operational costs, inefficient reimbursements, and reduced financial control.

5.2 Goal of the Dashboard

Provide a centralized view of healthcare claims metrics

Monitor total insurance payouts and patient contributions

Identify high-cost claim categories and demographics

Analyze provider performance and claim volumes

Track financial efficiency and reimbursement trends

Enable data-driven healthcare decision-making

5.3 Walkthrough of Key Visuals
🔹 KPI Cards

Displays:

Total Insurance Provided

Total Patient Payment

Average Insurance Payment

Average Patient Payment

Average Length of Stay

Provides an executive snapshot of financial and operational performance.

🔹 Claims by Claim Type (Bar/Column Chart)

Visualizes distribution of claims across different claim categories.
Helps identify dominant or high-cost treatment types.

🔹 Insurance vs Patient Contribution (Stacked Column / Donut Chart)

Compares insurance-covered amounts vs patient-paid amounts.
Helps understand dependency ratio and revenue mix.

🔹 Claims by Age Group

Breakdown of claims across age segments.
Identifies high-risk or high-utilization demographics.

🔹 Provider Performance Analysis

Displays:

Claims per provider

Insurance amount by provider

Average payment per claim

Helps benchmark provider efficiency and cost impact.

🔹 Disease / Treatment Analysis

Shows claim distribution by disease type.
Identifies dominant medical conditions driving claims.

🔹 Length of Stay Analysis (Line / Column Chart)

Analyzes average hospital stay duration.
Helps evaluate operational efficiency and care intensity.

🔹 Drill-through: Provider Deep Dive

Enables detailed analysis of:

Individual provider claim trends

Payment breakdown

Disease distribution

Average cost per claim

5.4 Business Impact & Insights

✔ Improved visibility into healthcare claim patterns
✔ Identification of high-cost age groups and claim types
✔ Better understanding of insurance vs patient payment distribution
✔ Provider performance benchmarking
✔ Enhanced financial monitoring and cost optimization
✔ Data-backed strategic healthcare planning

6. Deployment

Data cleaned and transformed in Power Query

Star schema data model implemented

DAX measures created for KPIs and analytics

Dashboard published to Power BI Service

Scheduled data refresh configured
