Tata Motors Car Sales Analytics Report

1) PROJECT OBJECTIVE:
            The primary objective of this project is to design and develop an end-to-end Sales Analytics Dashboard for Tata Motors using a structured Star Schema. This report provides actionable business intelligence across sales performance, regional trends, EV adoption, dealer efficiency, customer behavior, and financial patterns — enabling data-driven decision making for sales managers, regional heads, and business executives.

2) Data Cleaning & Transformation Summary:
Tool Used: Power Query — Power BI Desktop

Issues Found & Fixed:
 1. Removed Duplicates using primary key columns.
 2. Removed columns which are not necessary for analysis purpose.
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

3) Dashboard Creation:
               Developed an interactive Tata Motors Sales Dashboard in Power BI to analyze vehicle sales, revenue, profitability, dealer performance, customer behavior, and order cancellations. Performed data cleaning and transformation using Power Query, designed a star schema data model, and created DAX measures and KPIs. The dashboard includes KPI Cards, Line Charts for sales trends, Bar Charts for model and dealer performance, Map Visuals for regional analysis, Donut Charts for payment mode distribution, and Decomposition Tree and Key Influencers visuals for root cause analysis. The solution enables management to monitor business performance and make data-driven decisions.

4) KEY INSIGHTS DISCOVERED:
   1. Revenue Insights:
            Total revenue across FY2019-25 crossed ₹700+ Crores.
            Curvv EV is the highest revenue generating model contributing ~15% of total sales.
            Q4 (Jan-Mar) Quarter generates more than other quarters.
            2020 recorded highest ever annual revenue.

   2. EV Insights:
            EV sales were highest in 2020 then kept dropping sharply till 2024.
            Curvv EV Nexon Ev is the best selling electric vehicle across all years.
            South India leads EV adoption with Karnataka, Andhra Pradesh and Tamil Nadu in top 3 states.
      
  3. Regional Insights:
            Kerala is the top revenue state contributing ~18% of total sales.
            North has highest gross sales and was 146.09 % highest than East which has lowest sales.
            Gross sales and profit are positively correlated each other.

  4. Customer Insights:
            Sales are distributed nearly same across all age groups.
            10L-20L income band customers are most likely to choose finance over cash.
            loyalty tier customers have lowest cancellation rate compared with without loyalty  tier.

5) BUSINESS RECOMMENDATIONS:
1. EV Expansion Strategy
            Fast track EV dealer certification in East and North regions
            Launch EV awareness campaigns in cities like Delhi, West Bengal, Telangana.
            Partner with state governments for EV subsidy awareness programs.

2. Regional Growth Strategy
            Open 15-20 new dealerships in underserved East region states.
            Launch Bihar and West Bengal specific models with lower price points.
            Create regional sales targets aligned with population and income data.

3. Customer Retention Strategy
            Launch Tata Motors Loyalty App with points for service visits and referrals.
            Convert Bronze tier customers to Silver with targeted exchange offers.
            Send personalized upgrade offers to customers who bought entry models 3+ years ago.

4. Cancellation Reduction Strategy
            Implement mandatory test drive policy before booking confirmation. From analysis, i found that most
            of the orders were cancelled where test drive was not taken.
            Introduce small booking token amount to reduce casual cancellations.
            Send automated delivery updates to keep customer engaged post booking

6. Dealer Performance Strategy
            Upgrade Silver dealers to Gold with training and incentive programs.
            Share best practices of top 10 dealers with underperformers.
            Introduce monthly dealer scorecards tracking revenue, rating, and delivery days.
            Penalize dealers with delivery > 7 days and reward those under 3 days.

7. Finance & Pricing Strategy
            Introduce 84-month tenure option for premium models to reduce EMI burden
            Expand Tata Motors Finance subvented schemes during slow Q1 months.
            Offer zero down payment schemes for loyal Gold tier customers
            Launch corporate lease programs targeting large enterprises.

8. Data & Operations Strategy
            Fix dealer DMS system to prevent duplicate entries and missing invoices.
            Make invoice generation mandatory at point of booking.
            Add system validation to reject negative discount entries.

6) Conclusion:
               This project successfully demonstrates a complete end-to-end Business Intelligence solution built on a Star Schema for Tata Motors. Starting from raw messy data with multiple quality issues, the data was cleaned and transformed using Power Query, modeled into a structured star schema with one fact table and six dimension tables, and analyzed using DAX measures to produce meaningful business insights.
