# Discount_Strategy_Simulation
Scenario-based Power BI dashboard using What-If parameters and advanced DAX to model discount impact on churn, revenue retention, and ROI optimization.

# Discount_Strategy_Simulation
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Tools & Technologies](#tools/&-technology)
- [Key Features](#key-features)
- [Data Analysis & Visualization](#data-analysis-visualization)
- [Inights from 10% and 20% discount scenarios](#insights-from-10%-and-20%-discount-scenarios)
- [Business Implications & Recommendations](#business-implications-recommendations)
- [Conclusion](#conclusion)

## Project Overview:

This project explores the impact of strategic discounting on customer churn in a telecommunications company. Using **Power BI’s What-If parameters** and **advanced DAX calculations**, we simulate how different discount levels affect customer retention, segment behavior, and revenue.

The result? A dynamic, scenario-based dashboard that empowers decision-makers with data-driven insights.

## Objectives:

- Analyze whether discounts lead to a positive ROI by reducing churn.
- Identify customer segments most responsive to discount strategies.
- Simulate real-time discount scenarios using interactive sliders.

## Tools & Technologies:

- **Power BI**
- **DAX (Data Analysis Expressions)**
- **Scenario Analysis & What-If Parameters**
- **Custom Tooltips for Metrics Explanation**

## Key Features

### Discount Impact Simulator:

An interactive Power BI dashboard using a What-If parameter slider that simulates discount levels (0% to 50%) and shows:

- Overall Churn Rate
- Churn by Contract Type, Spending Group, Payment Method
- Estimated Revenue Retained (Retention Value)
- Discount Costs vs ROI

## What-If Parameter Implementation:
- Discount Slider
![Discount Slider](https://github.com/user-attachments/assets/4a604c2c-3f24-49f2-9ae7-ea6270894895)
- Discount Slider Value
![Discount Slider Value](https://github.com/user-attachments/assets/15c7a129-c1cd-4ac2-bb0f-6f38b6f0fb5d)

## Advanced DAX Measures:

Key calculations include:

- `Churn Reduction`
![Churn Reduction](https://github.com/user-attachments/assets/9100a96c-89e6-45d4-b363-c75f05b6ed3e)
- `Customers Retained`
 ![Customer Retained](https://github.com/user-attachments/assets/b331798c-24a4-46c9-a640-8a431bc0acda) 
- `Retention Value`
![Retention Rate](https://github.com/user-attachments/assets/8e904804-bc5d-4413-99c2-487ae745db3a)
- `Discount Cost`
![Discount Cost](https://github.com/user-attachments/assets/17ec99b3-ce48-4e89-aa42-246077462b4c)
- `Discounted CLV`
![Discounted CLV](https://github.com/user-attachments/assets/d760b564-fe69-43ff-8454-4f51136ece1f)
- `Net Revenue Impact`
![Net Revenue Impact](https://github.com/user-attachments/assets/ae814a42-c4b0-4079-aac8-5b871c8c43df)
- Segment-specific churn adjustments
![Segment Discounted Churn](https://github.com/user-attachments/assets/bfee82b3-9096-4e0d-8cab-3daea640e7cf)

## Tooltip Customization:

- Report page tooltips explaining ROI, CLV impact, and percentage changes
![Retention Value](https://github.com/user-attachments/assets/26fe80ab-f050-445c-951f-6e5e2f84e569)
  
# Data Analysis & Visualization:
![0% Discount](https://github.com/user-attachments/assets/044f8aa2-95a9-46eb-9dd5-66cf4d34fa8f)
## Interactive Scenario Analysis:

- 10% Discount Scenario
![10% Discount](https://github.com/user-attachments/assets/2940b72b-7197-47e9-b000-dc61b8fcb42d)

- 20% Discount Scenario
![20% Discount](https://github.com/user-attachments/assets/abcae8a7-3b65-4a6b-8428-4f311291cd5a)

## **Inights from 10% and 20% discount scenarios:**
1.	**Overall Impact Comparative Discount Scenarios**
- The baseline customer churn rate is **26.54%** without discounts
-	A 10% discount reduces overall churn from **26.54%** to 2**6.40% (0.14 percentage points)**
- Doubling the discount to **20% further reduces churn to **26.27% (0.27 percentage points total)**
While the absolute churn reduction appears modest, the financial impact tells a compelling story:
- At **10% discount:** **$456** in discount costs generates **$7,262** in retention value **(15.9x ROI)**
-	At **20%** discount:** **$912** in discount costs generates **$15,000** in retention value **(16.4x ROI)**
This suggests that higher discount levels could potentially yield even better returns, though further analysis would be needed to find the true optimization point.

2. **Contract-Based Analysis**
- **Month-to-month** contracts have the highest churn rate at **42.71%**
-	10% discount reduces it slightly to **42.50%** (-0.21%)
-	20% discount reduces it to **42.28%** (-0.43%)
- **One-year contracts** show moderate churn at **11.27%**
-	10% discount: **11.21%** (-0.06%)
-	20% discount: **11.16%** (-0.11%)
- **Two-year contracts** have the lowest churn at **2.83%**
- 10% discount: **2.82%** (-0.01%)
-	20% discount: **2.80%** (-0.03%)
3. **Spending Group Analysis**
**High-spending customers** show the highest churn (**35.36%**)
-	10% discount: **35.18%** (-0.18%)
-	20% discount: **35.01%** (-0.35%)
**Medium-spending customers** have moderate churn (**24.35%**) and demonstrate similar discount sensitivity.
-	10% discount: **24.23%** (-0.12%)
-	20% discount: **24.11%** (-0.24%)
Low-spending customers demonstrate the lowest churn (9.80%) with minimal discount impact.
- 10% discount: **9.75%** (-0.05%)
-	20% discount: **9.70%** (-0.10%)
4. **Payment Method Analysis**
**Electronic check** payments show the highest churn (**45.29%**)
-	10% discount: **45.06%** (-0.23%)
-	20% discount: **44.83%** (-0.46%)
**Mailed check** payments have moderate churn (**19.11%**)
-	10% discount: **19.01%** (-0.10%)
-	20% discount: **18.92%** (-0.19%)
**Bank transfer** payments show lower churn (**16.71%**)
-	10% discount: **16.63%** (-0.08%)
-	20% discount: **16.54%** (-0.17%)
**Credit card** payments demonstrate the lowest churn (**15.24%**)
-	10% discount: **15.17%** (-0.07%)
-	20% discount: **15.09%** (-0.15%)

This presents an opportunity for targeted discount strategies based on payment preference.
# Business Implications & Recommendations:

This analysis reveals several strategic opportunities:
1.	**Positive ROI Across Scenarios:** Even at higher discount percentages, the retention value consistently exceeds discount costs by a significant margin.
2.	**Target high-impact segments:** Focus discount resources specifically on month-to-month contracts and electronic check users, which show the largest absolute improvement from increased discounts.
3.	**Investigate high-spending customer churn factors:** Despite being the most valuable segment, high-spending customers show alarming churn rates (**35.36%**). Conduct research beyond pricing to understand drivers of dissatisfaction.
4.	**Develop segment-specific retention strategies:** Different segments respond differently to discounts; for example, electronic check users show the most significant improvement with higher discounts (-0.46% at a 20% discount).
5.	**Incentivize contract upgrades:** Given the dramatic difference in churn between contract types (42.71% for month-to-month vs. 2.83% for two-year), develop strong incentives for customers to commit to longer contracts.
6.	**Address payment method vulnerabilities:** Implement targeted strategies to either convert electronic check users to more stable payment methods or create special retention programs for this high-risk segment.
7.	**Explore alternative retention tactics:** Given the limited impact of price discounts across all segments, test non-price retention strategies such as service enhancements, loyalty programs, or improved customer support.

# Conclusion:
This analysis demonstrates that even small reductions in churn rate can translate to significant business value when properly targeted. The data indicates that a one-size-fits-all discount strategy isn't the best, even though discounts do somewhat lower churn, particularly among high spenders and vulnerable segments like month-to-month customers. A layered approach that combines smart discounting, contract incentives, and seamless payment methods is likely to yield better long-term results.
This project showcases how data-driven scenario modeling can transform retention strategies from guesswork into measurable business value.




