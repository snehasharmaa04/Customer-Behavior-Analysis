# Customer-Behavior-Analysis
End-to-end Customer Behavior Analysis using Python (Pandas) for data cleaning, PostgreSQL for relational storage &amp; querying, and Power BI for interactive dashboarding.
An end-to-end data analytics project exploring customer purchase patterns, demographics, product categories, and subscription statuses. Built using *Python (Pandas)* for data preprocessing, *PostgreSQL* for relational data storage & querying, and *Power BI* for interactive visual reporting.

**Tech Stack**
* Data Processing & Cleaning: Python (Pandas)
* Database & Querying: PostgreSQL
* Visualization & Reporting: Microsoft Power BI (DAX, Data Modeling)

**Key Metrics & KPIs**
* Total Customers: 3.9K
* Average Purchase Amount: $59.76
* Average Review Rating: 3.75 / 5.0
* Subscription Breakdown: 27% Subscribed vs. 73% Non-Subscribed

**Key Insights & Dashboard Features:**

1. Category Performance:
   * Analyzed Revenue and Total Sales across major segments: Clothing, Accessories, Footwear, and Outerwear*.
   * Clothing and Accessories drive the largest share of overall sales and revenue.

2. Demographic Analysis (Age Groups):
   * Categorized customers into *Young Adult, Middle-aged, Adult, and Senior.
   * Visualized spending behavior and transaction volume across age demographics.

3. Interactive Slicers & Filtering:
   * Dynamic filtering by Gender (Female, Male).
   * Seasonal trend exploration across Fall, Spring, Summer, and Winter.
   * Slicers for Subscription Status and Product Categories.

**Project Workflow (ETL Pipeline)**

1. Data Cleaning & Transformation (Python / Pandas):
    * Handled missing/null values and verified data integrity.
    * Standardized categorical variables and prepared clean datasets for relational schema design.

2. Database Management (PostgreSQL):
   * Created tables and loaded structured data into PostgreSQL.
   * Executed SQL aggregation queries to validate KPI numbers and compute baseline summaries.

3. Dashboard & Modeling (Power BI):
   * Connected Power BI to PostgreSQL / cleaned datasets.
   * Created calculated measures using *DAX* (Average Order Value, Customer Counts, Subscription Ratios).
   * Designed an intuitive, high-contrast dashboard layout with synchronized slicers.
