## Telco-Churn

**Project Overview** 

This project analyzes customer churn behavior for a telecom company using an end-to-end data analytics workflow. The goal is to identify key drivers of churn and provide actionable business insights to improve customer retention.

**Objectives**

- Analyze customer churn patterns
- Identify high-risk customer segments
- Understand key factors influencing churn
- Provide data-driven business recommendations

**Tools & Technologies**
- Excel – Data cleaning & preprocessing
- Google BigQuery – SQL analysis
- Tableau – Data visualization & dashboarding
- GitHub – Project documentation & version control

  **Dataset**
- Source: Kaggle Telco Customer Churn Dataset
- Contains customer demographics, services, billing, and churn status

  **Data Workflow**
  1. Data Collection
- Downloaded dataset from Kaggle
2. Data Cleaning (Excel)
- Handled missing values
- Created new features:
- Churn Flag (0/1)
- Tenure Group
- Monthly Charge Group
- Standardized categorical values
3. Data Analysis (SQL – BigQuery)
- Calculated churn rate
- Segmented customers by:
  - Contract type
  - Tenure
  - Monthly charges
  - Payment method
- Identified high-risk customer groups
4. Data Visualization (Tableau)
- Built interactive dashboard
- Designed KPIs and segmentation views
- Highlighted key churn drivers

**Key Metrics**
- Total Customers
- Churn Rate
- Average Monthly Charges

  **Dashboard Features**
- Churn by Contract Type
- Churn by Tenure Group
- Churn by Monthly Charges
- Churn by Internet Service
- Payment Method Analysis
- Service Impact (Tech Support, Security, etc.)
- Churn Risk Heatmap (Contract × Internet Service)

  **Key Insights**
- Customers on month-to-month contracts have significantly higher churn rates
- New customers (0–12 months) are the most likely to churn
- Customers with higher monthly charges show increased churn risk
- Lack of tech support and security services correlates with higher churn
- Electronic check users tend to churn more frequently

**Business Recommendations**
- Introduce incentives for long-term contracts
- Improve onboarding experience for new customers
- Offer bundled services (e.g., tech support) to increase retention
- Review pricing strategy for high-cost plans
- Target high-risk segments with retention campaigns

  **Dashboard Preview**
![Image Alt](https://raw.githubusercontent.com/zaher-insights/Telco-Churn/b73a02a937963053d2bcaab698c06c4e50436071/Telco%20Churn.png)
![Image Alt](https://raw.githubusercontent.com/zaher-insights/Telco-Churn/3d0c6dcc9030b873f871d565aaa45ce2424b4eec/Dashboard1.png)

**How to Reproduce**
1. Download dataset from Kaggle
2. Clean data in Excel
3. Upload to BigQuery and run SQL analysis
4. Connect Tableau to dataset
5. Build dashboard using calculated fields and visualizations


**Project Highlights**
- End-to-end analytics pipeline (Excel → SQL → Tableau)
- Real-world business problem (customer churn)
- Actionable insights and recommendations
- Interactive data visualization

 **What I Learned**
- Handling data type inconsistencies across tools
- Translating business questions into SQL queries
- Designing dashboards for stakeholder decision-making

**Author**
*Zaher Ahmed*
- GitHub: [[profile link](https://github.com/zaher-insights/Netflix-Insights-)]
- LinkedIn: [[LinkedIn link](https://www.linkedin.com/in/zaher-ahmed-777506199/)]
  
