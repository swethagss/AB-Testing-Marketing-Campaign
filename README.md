# AB Testing Marketing Campaign 

![Image](https://github.com/user-attachments/assets/4c992213-232b-4a0c-b14c-a066f5663a43)

## Project Background
This project involves conducting AB testing to evalute the performance of two marketing campaigns **Facebook and AdWords** for an online retail business.
The primary goal is to determine which platform yeilds better results in terms of clicks, conversions and and overall cost-effectiveness. By identifying the most effective platform, marketing agency can allocate our resources more efficiently and optimize their advertising strategies to deliver better outcomes for the clients.

---
## Problem Statement
- Identify which platform generates better clicks, conversions, and cost-effectiveness.
- Provide data-driven recommendations for marketing budget allocation.
---
## Data Description
Dataset contains daily campaign data for 2019 with key metrics
  - Ad Views, Clicks, Conversions
  - CTR (Click-Through Rate), Conversion Rate, Cost per Click (CPC)
  - Ad Spend per Campaign

---

## Approach 
  - Conducted **data cleaning and exploratory analysis**
  - Calculated key metrics: **CTR, Conversion Rate, CPC, ROI**
  - Performed **AB testing / hypothesis testing** to compare campaigns
  - Built **linear regression models** to estimate conversions from clicks
  - Visualized results with **Python (Matplotlib, Seaborn)**

## Key Insights
  - **Facebook Ads**: Fewer clicks/views but higher conversion rate and more consistent high-conversion days
  - **AdWords**: Higher reach (views & clicks) but lower conversion rate and high variability
  - **Correlation Analysis:**
    - Facebook clicks vs conversions: r = 0.87 → strong positive relationship
    - AdWords clicks vs conversions: r = 0.45 → moderate positive relationship
  - **Trend Analysis:**
    - Mondays & Tuesdays see higher conversions
    - Seasonal fluctuations observed; Feb, Apr, May, Jun, Aug, Nov have lower conversions
  - **Cost per Conversion (CPC):**
    - May & Nov are more cost-effective
    - February shows highest CPC → consider optimizing spend
## 📈 Key Visualizations

<img width="1088" height="468" alt="Image" src="https://github.com/user-attachments/assets/b992ca7c-ca58-4536-ad80-247077e9d9c8" />

---
### Click-Through Rate Distribution
<img width="1086" height="481" alt="Image" src="https://github.com/user-attachments/assets/c638a584-4e58-4d37-bff6-88ea4528356d" />

---
### Regression Analysis 
<img width="702" height="516" alt="Image" src="https://github.com/user-attachments/assets/e3bb45bb-5182-4223-8b8f-55cb4a7354c7" />

---


## Outcome / Business Impact
  - Determined Facebook as the more effective platform for conversions
  - Provided budget optimization recommendations based on CPC and conversion trends
  - Created dashboards and visual reports for marketing stakeholders
  - Regression model helps predict conversions from clicks for better campaign planning


  






