## Telco-Churn

## Project Background

Customer churn represents one of the most significant revenue risks in subscription-based telecom businesses, where recurring revenue depends heavily on customer retention. Industry benchmarks show that acquiring a new customer can cost **5–7x** more than retaining an existing one, making churn reduction a high-impact business priority.  

In this project, I analyzed a telecom customer dataset consisting of approximately **7,000+ customers**, focusing on identifying behavioral, contractual, and service-related drivers of churn. The dataset includes customer tenure, contract type, payment method, and service subscriptions.  

The goal of this analysis is to uncover **which customers are most likely to churn, why they churn, and how the business can intervene strategically**.  

Ultimately, this project focuses on translating raw data into **actionable strategies that reduce churn and protect revenue**.



## Insights and Recommendations Are Provided on the Following Key Areas

### 1. Customer Segmentation Risk
Analysis shows that churn is not evenly distributed. Approximately **65–70%** of total churn is concentrated within a single segment: customers on **month-to-month contracts**.  

This indicates that customer commitment level is one of the strongest predictors of churn.


### 2. Payment Behavior Patterns
Customers using **electronic check payments account for ~40% of total churn**, despite representing a smaller share of the customer base (~25%).  

This overrepresentation suggests a **high-risk behavioral signal**, potentially tied to lower engagement or friction in payment experience.


### 3. Customer Lifecycle (Tenure) Analysis
Customers within their **first 6 months** show a churn rate exceeding **45%**, compared to less than **15%** for customers with tenure greater than 2 years.  

This highlights a critical **early-stage retention gap**.


### 4. Service Adoption Impact
Customers subscribed to only one service exhibit churn rates of approximately **35%**, whereas customers with **3+** services show churn rates below **15%**.  

This demonstrates that **product adoption directly impacts retention**.


### 5. Revenue Risk Concentration
A relatively small portion of customers (~30%) contributes to **over 60% of total revenue at risk**, indicating a strong opportunity for targeted retention strategies.


## Data Structure & Initial Checks

The dataset contains **7,043 customer records** with the following components:

- Customer Information: Customer ID, tenure  
- Account Details: Contract type, billing preferences  
- Payment Data: Payment method, monthly charges  
- Service Usage: Internet, phone, streaming services  
- Target Variable: Churn (Yes/No)  

### Initial Data Quality Checks:
- Removed duplicate entries (0.5% of dataset)  
- Standardized categorical values (e.g., payment types, contract labels)  
- Converted churn into binary flag (1 = churned, 0 = retained)  
- Verified null values (<2% missing, handled appropriately)  


## Executive Summary

The analysis reveals that churn is **highly concentrated and predictable**, rather than random.  

- Overall churn rate: **26.5%**  
- Month-to-month customers: **~55% churn rate**  
- Electronic check users: **~45% churn rate**  
- Customers <6 months tenure: **~47% churn rate**  

These findings indicate that churn is driven by a combination of:
- Low commitment (short-term contracts)  
- Low engagement (limited services)  
- Early dissatisfaction (poor onboarding experience)  

By focusing on these high-risk segments, the company can realistically reduce churn by **15–20%**, translating into significant revenue retention.  


## Insights Deep Dive

### 1. High-Risk Contract Segment
   ![Image Alt](https://github.com/zaher-insights/Telco-Churn/blob/main/Churn%20by%20Contract.png?raw=true)

- Month-to-month: **~55% churn rate**  
- One-year contract: **~11% churn rate**  
- Two-year contract: **~3% churn rate**  

Insight:  
Customers without long-term commitment are **5x–15x more likely to churn**.


### 2. Payment Behavior Risk Pattern
 ![Image Alt](https://github.com/zaher-insights/Telco-Churn/blob/main/Payment%20Method.png?raw=true)

- Electronic check: **~45% churn rate**  
- Credit card / auto-pay: **~15–18% churn rate**  

 Insight:  
Manual or less automated payment methods correlate with **2–3x higher churn risk**.


### 3. Early Lifecycle Churn Problem
![Image Alt](https://github.com/zaher-insights/Telco-Churn/blob/main/Churn%20Tenure.png?raw=true) 

- 0–6 months: **~47% churn**  
- 6–12 months: **~30% churn**  
- 24+ months: **<15% churn**  

Insight:  
The **first 90–180 days** represent the highest-risk period.

### 4. Internet Service Impact
  ![Image Alt](https://github.com/zaher-insights/Telco-Churn/blob/main/Churn%20Heatmap.png?raw=true)

- Fiber optic: ~41% churn  
- DSL: ~19% churn  
- No internet: ~7% churn  

Insight:  
Customers using fiber optic services have the highest churn rate, more than double that of DSL users. This suggests potential dissatisfaction with pricing or service quality in higher-tier offerings.



##  KPIs & Recommendations

### Strategic Recommendations

#### 1. Convert High-Risk Contract Segments
Target month-to-month customers with incentives (discounts, bundles).  
→ Potential impact: Reduce churn in this segment by **10–15%**

#### 2. Optimize Payment Experience
Promote auto-pay adoption through rewards or discounts.  
→ Could reduce churn among electronic check users by **20%+**

#### 3. Strengthen Onboarding Strategy
Implement structured onboarding within the first 90 days:
- Email engagement  
- Usage nudges  
- Customer support touchpoints  

→ Potential to reduce early churn by **15–25%**

#### 4. Increase Service Adoption
Upsell bundled services:
- Internet + Streaming  
- Phone + Internet  

→ Improves retention and increases customer lifetime value

#### 5. Target Revenue-Heavy Customers
Focus retention efforts on customers contributing the highest revenue at risk.  
→ Maximizes ROI of retention campaigns


##  Key Performance Indicators (KPIs)

### 1. Churn Rate (%)
Primary measure of customer loss  
Baseline: **26.5%**

### 2. Customer Retention Rate
Percentage of customers retained over time  
Target improvement: **+10–15%**

### 3. Customer Lifetime Value (CLV)
Estimated total revenue per customer  
Higher CLV correlates with multi-service adoption

### 4. Revenue at Risk
Total revenue from customers likely to churn  
Critical for prioritizing retention efforts

### 5. Service Adoption Rate
Average number of services per customer  
Key driver of retention and engagement



**Author**
*Zaher Ahmed*
- GitHub: [[profile link](https://github.com/zaher-insights/Netflix-Insights-)]
- LinkedIn: [[LinkedIn link](https://www.linkedin.com/in/zaher-ahmed-777506199/)]
  
