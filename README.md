# Job-Market-Trends-Forecasting

This project analyzes job market trends using **dbt**, **Snowflake**, and **Airflow**, providing insights into job demand, salary trends, and market dynamics.

## **Project Overview**

1. **Data Pipeline**:
   - **Source**: Raw job listing data from Snowflake.
   - **Transformation**: dbt models process and analyze data.
   - **Visualisation**: Charts/Dahboards captures changes in job listings over time.

2. **Key Output**:
   - **Job Salary Trends Table**: Combines insights on average salaries, job demand, and locations for analytics.

3. **Orchestration**:
   - **Airflow**: Automates the ETL process and ensures efficient pipeline execution.

## **Key Features**
- Identify monthly salary trends by location and job title.
- Evaluate job demand to support workforce and hiring strategies.
- Real-time data snapshots to track evolving job market trends.

## **Technologies**
- **dbt**: Transformations and modeling.
- **Snowflake**: Data warehouse for scalable storage and querying.
- **Airflow**: Task scheduling and orchestration.

## **Getting Started**
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Set up the environment:
   - Configure `profiles.yml` for dbt Snowflake.
   - Update Airflow DAGs to schedule pipelines.
3. Run dbt models:
   ```bash
   dbt debug
   ```
   ```bash
   dbt run
   ```
5. Visualize analytics in BI tools.

## 📊 Visual Dashboard Insights

### 🔍 Job Market Analysis
It visualizes job salary trends , job demands, average salary and real time jon insights specific to various industries.
<p align="center">
  <img src="https://github.com/user-attachments/assets/30598ac0-9518-4edb-9403-24b7219834b9" alt="Job Market Analysis Dashboard" width="800">
</p>

### ⚖️ Comparing Two Job Roles
It  Provides comparisons of  job role based on salary, company and trending months.
<p align="center">
  <img src="https://github.com/user-attachments/assets/6cdb2348-12bb-438c-bd5c-6cad61eedfe7" alt="Comparing Two Job Roles" width="800">
</p>

### ⏱️ Real-Time Job Market Insights
Displays live job openings by location, salary and companies.
<p align="center">
  <img src="https://github.com/user-attachments/assets/ba7b1ed1-ad2f-4431-82f1-d89722f2c0bb" alt="Real Time Job Market Insights" width="800">
</p>

## **Future Enhancements**
- Integrate with more job listing platforms.
- Expand analysis to include skill-based insights.

 
