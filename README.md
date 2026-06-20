Tata Motors Car Sales Analytics Report

1) PROJECT OBJECTIVE:
            The primary objective of this project is to design and develop an end-to-end Sales Analytics Dashboard for Tata Motors using a structured Star Schema. This report provides actionable business intelligence across sales performance, regional trends, EV adoption, dealer efficiency, customer behavior, and financial patterns — enabling data-driven decision making for sales managers, regional heads, and business executives.

2) Data Cleaning & Transformation Summary
Tool Used: Power Query — Power BI Desktop

Issues Found & Fixed:
 1. Removed Duplicates using primary key columns.
 2. Removed columns which i thought to be not necessary for analysis purpose.
 3. Trimmed text columns.
 4. Captitalized each text column for tranformation purpose.
 5. Data type of columns changed wherever necessary.
 6. Gender column had M and F values. Replaces M with Male and F with Female for better readability and understanding
 7. Existing customer column removed. People usually buy cars 1 to 2 times in lifetime. So i considered this column won't 
 affect analysis.
 8. Weekeend and holidays columns have had values as 0 and 1 which is not understandable for non technical people.
 So, i replaced 1 with 'Yes' and 0 with 'No'.
 9. There was contact phone column present. i removed that column as its not necessary for analysis purpose.
 Trimmed text columns.
 10. Negative Values — DiscountAmount_INR had approximately 5% negative values due to data entry errors. Converted all negative discounts to absolute positive values using a custom column in Power Query.
 11.  Null values replaced according to data type of column.
 12. Perfomed splitting and Merging columns wherever required.

KEY INSIGHTS DISCOVERED
💰 Revenue Insights

Total revenue across FY2019-25 crossed ₹850+ Crores
Nexon is the highest revenue generating model contributing ~28% of total sales
Q3 (Oct-Dec) festive season consistently drives 35% higher sales than other quarters
FY2023-24 recorded highest ever annual revenue with 22% YOY growth

⚡ EV Insights

EV sales share grew from 8% in FY2020 to 31% in FY2025
Nexon EV is the best selling electric vehicle across all years
South India leads EV adoption with Karnataka and Tamil Nadu in top 3 states
EV certified dealers generate 2.4x more revenue than non-certified dealers

🗺️ Regional Insights

Maharashtra is the top revenue state contributing ~18% of total sales
West region leads overall with Mumbai, Pune, and Ahmedabad driving volume
East region (Bihar, West Bengal) is significantly underserved with only 8% revenue share
North India shows highest cancellation rate at 16% vs national average of 14%

👥 Customer Insights

26-35 age group is the largest buyer segment at 38% of all sales
10L-20L income band customers are most likely to choose finance over cash
Customers who took test drives converted 2.1x better than those who didn't
Gold loyalty tier customers have lowest cancellation rate at only 6%

🏪 Dealer Insights

Top 10 dealers contribute 42% of total revenue
Platinum tier dealers have 4.2 days average delivery vs 8.7 days for Silver tier
156 out of 250 dealers are EV certified but account for 89% of EV revenue
Dealers established before 2012 show 3x better target achievement rates

💳 Finance Insights

68% of customers prefer finance over cash purchase
Tata Motors Finance is most preferred with 31% market share among financed deals
48-month tenure is most popular loan period
Subvented scheme deals show 40% lower cancellation rate

📦 Operational Insights

Average delivery time is 5.2 days nationally
Customers receiving delivery within 3 days give 4.6 avg rating vs 3.1 for 10+ days
Digital channel bookings have highest cancellation rate at 18%
Showroom walk-ins convert with lowest cancellation at 9%


💡 BUSINESS RECOMMENDATIONS
1. EV Expansion Strategy

Fast track EV dealer certification in East and North regions
Launch EV awareness campaigns in Tier 2 cities like Lucknow, Jaipur, Nagpur
Partner with state governments for EV subsidy awareness programs
Build charging infrastructure maps in Power BI to identify coverage gaps

2. Regional Growth Strategy

Open 15-20 new dealerships in underserved East region states
Launch Bihar and West Bengal specific models with lower price points
Create regional sales targets aligned with population and income data
Appoint regional sales champions to drive accountability

3. Customer Retention Strategy

Launch Tata Motors Loyalty App with points for service visits and referrals
Convert Bronze tier customers to Silver with targeted exchange offers
Send personalized upgrade offers to customers who bought entry models 3+ years ago
Introduce corporate fleet programs to target IT companies in Bengaluru and Hyderabad

4. Cancellation Reduction Strategy

Implement mandatory test drive policy before booking confirmation
Introduce small booking token amount to reduce casual cancellations
Send automated delivery updates to keep customer engaged post booking
Train Digital channel sales team on better customer qualification

5. Dealer Performance Strategy

Upgrade Silver dealers to Gold with training and incentive programs
Share best practices of top 10 dealers with underperformers
Introduce monthly dealer scorecards tracking revenue, rating, and delivery days
Penalize dealers with delivery > 7 days and reward those under 3 days

6. Finance & Pricing Strategy

Introduce 84-month tenure option for premium models to reduce EMI burden
Expand Tata Motors Finance subvented schemes during slow Q1 months
Offer zero down payment schemes for loyal Gold tier customers
Launch corporate lease programs targeting large enterprises

7. Data & Operations Strategy

Fix dealer DMS system to prevent duplicate entries and missing invoices
Make invoice generation mandatory at point of booking
Add system validation to reject negative discount entries
Implement real-time Power BI refresh for daily sales monitoring
