#### Credit Card Transaction Report – Power BI Dashboard

This interactive dashboard was built using Power BI to analyze and visualize credit card transaction data for a financial institution. The goal was to provide clear, actionable insights for stakeholders to understand revenue patterns, customer behavior, and product performance.

#**Development Overview**

**Data Modeling & ETL:**
Raw transactional data was imported, cleaned, and transformed using Power Query.
Relationships were established among tables such as transactions, customers, card categories, and demographics.
Measures and calculated columns were created using DAX for KPIs like Total Revenue, Interest Earned, Transaction Count, and Average Transaction Volume.

**User Experience & Design:**
A clean and intuitive layout was designed for better readability using custom bookmarks, slicers, and synced visuals.
Emphasis was given to comparative metrics across time (quarters), gender, card category, and demographic attributes.

**Key Functionalities Used**
Dynamic Slicers:
Multi-select filters for Card Category, Quarter, Income Group, Gender, and Week Start Date allow users to slice the data interactively.

Drill-Down Capabilities:
Users can explore data across various dimensions such as Expenditure Type, Use of Chip, Customer Job, and Education Level.

Visual Insights:
Combination of bar charts, pie charts, and line graphs helps interpret trends and correlations clearly.
Quarterly trends highlight seasonality in both transaction volume and revenue.

Row-Level Security (RLS):
Implemented Row-Level Security using the USERPRINCIPALNAME() DAX function to ensure data is filtered and shown based on the logged-in user’s credentials.
This ensures confidentiality and enables personalized views for different users or departments.

#**Insights Derived:**
Revenue by Gender: Females contribute slightly more (54.73%) to the total revenue than males (45.27%).
Transaction Channels: Swiping is the most common and revenue-generating method, contributing $36M.
Customer Demographics:Highest revenue comes from Graduates and Businessmen, indicating a financially active segment.
Bills, Entertainment, and Fuel are the top expenditure types.
Card Category Performance:Blue cards dominate the revenue contribution at $47M, significantly outperforming Silver, Gold, and Platinum.
Quarterly Trends:Revenue and transaction count show a consistent increase across quarters, with Q4 being the highest in both metrics.

#**Tools & Techniques Used:**
Power BI Desktop for development
Power Query for data transformation
DAX for creating custom metrics and dynamic KPIs
USERPRINCIPALNAME() for user-specific data filtering


#**Outcome:**
This dashboard enables business leaders and analysts to:
Monitor performance by card category and customer segment
Track trends and seasonality in transactions and revenue
Make data-driven decisions for marketing, credit policies, and customer engagement strategies
