# Fetch_Data_Analyst_Take_Home_Submission
**Project Overview**
This notebook focuses on analyzing Fetch Rewards transaction, user, and product data to uncover key trends, data quality issues, and business insights. The primary goals of this analysis are:
1. Identify data inconsistencies and missing values across tables
2. Analyze year-over-year growth trends and potential reasons for fluctuations
3. Examine brand and retailer performance to inform strategic business decisions
4. Propose actions for data cleaning and standardization to improve reporting accuracy
5. Suggest re-engagement and user acquisition strategies based on insights


**Dataset Overview**
The analysis is based on three primary datasets:
1. Transactions Data - Contains user purchase behaviour, including receipt details, purchase dates, and product information.
2. Users Data - Contains user demographic information, including account creation details.
3. Products Data - Provides product metadata, including barcode details and categorization.
   
**Key Data Quality Issues Identified**
1. Transactions Table: Duplicate receipt_ids, missing BARCODE values, mixed formats in FINAL_QUANTITY, and inconsistencies in SCAN_DATE.
2. Users Table: Missing BIRTH_DATE, LANGUAGE, and GENDER values, along with inconsistent category naming (e.g., Non-Binary vs. non_binary).
3. Products Table: Missing manufacturer and category data, placeholder values, and multiple BARCODEs for the same product.

**Business Insights & Trends**
1. User Growth Analysis: Fetch Rewards experienced peak growth of 820% in 2017, but growth declined by 42% in 2023 and 24% in 2024.
2. Brand Performance: The top-selling brands among long-term users include Annie’s Homegrown Grocery, Dove, and Barefoot.
3. Retailer Insights: Walmart is a major retailer among Fetch users, presenting an opportunity for strategic partnerships to improve engagement.
4. Revenue Growth Strategy: The declining user growth suggests potential market saturation, engagement drop-off, or competition. A focus on re-engagement campaigns and new merchant partnerships is recommended.

**Next Steps & Actionable Requests**
1. Product & Engineering: Address data inconsistencies and improve data standardization.
2. Marketing & Partnerships: Develop targeted re-engagement programs and assess high-performing states (Texas, Florida, and California) for new partnerships.
3. Analytics & Strategy: Dive deeper into user churn patterns and analyze retention challenges.
   
**How to Use This Notebook**
- Run each cell in sequence to clean and analyze the datasets.
- Adjust filtering and visualization parameters as needed.
- Use the final insights for business decision-making and strategy formulation.
  
Requirements
This notebook requires the following Python libraries:
- pandas
- numpy
- matplotlib
- jupysql

**Contact**
For any questions or contributions, please contact Sathwik Kanukuntla at sathwikk001@gmail.com.
