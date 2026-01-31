# Customer Churn Analytics Dashboard
1. Short Description
This dashboard analyzes why customers leave and predicts which ones are likely to churn next. It helps businesses move from reactive fixes to proactive retention.

2. Tech Stack
The dashboard was built using the following tools and technologies:

Power BI Desktop – Core platform for data visualization.

Power Query – Used for data cleaning, handling null values, and profiling customer data.

DAX – Developed complex measures for Churn Rate %, Predicted Churners, dynamic ranking of states.

Data Modeling – Built a star schema to connect customer demographics, geographic data, and service subscriptions.

File Format – .pbix for the interactive report and .png for documentation.

3. Data Source
The dataset consists of 824 total customers with detailed attributes including:

Demographics: Gender, Age Group, and State.

Account Info: Tenure (months), Contract Type (Month-to-month, One Year, Two Year), and Payment Method.

Services: Internet service, Online security, Device protection, and Paperless billing.

Financials: Monthly charges and Total Revenue.

4. Features / Highlights
• Business Problem 
Customer churn is a silent revenue killer. Without a clear view of why customers leave, businesses struggle to allocate marketing budgets effectively. Key unknowns included:

Which age groups are most likely to leave?

Do specific contract types (like Month-to-Month) correlate with higher churn?

What services (or lack thereof) are common among churned users?

• Goal of the Dashboard
To deliver an end-to-end analytical tool that:

Explains the Past: Identifies historical trends and churn drivers.

Predicts the Future: Lists specific Customer IDs at high risk of leaving (378 predicted churners identified).

• Walkthrough of Key Visuals
Dashboard 1: Summary (Historical Analysis)

KPI Ribbon: Displays Total Customers (824), Total Churn (234), and the current Churn Rate (28%).

Churn by Gender & Age: Highlights that while the gender split is relatively even, the 61+ age group has the highest churn rate at 32%.

Reasons for Churn: A pie chart identifying Competitors (41.88%) as the primary reason customers leave.

Service-Wise Behavior: A heatmap showing that customers without Online Security or Online Backup have significantly higher churn rates.

Dashboard 2: Prediction (Future Outlook)

Predicted Churner Count: Identifies 378 customers likely to churn.

Customer ID Table: A detailed list of at-risk customers with their Monthly Charges and Number of Referrals, allowing the sales team to take direct action.

Tenure Risk: A donut chart showing that 26% of predicted churners are in their first 6 months (the "danger zone").

• Business Impact & Insights
Retention Strategy: The data suggests a need for "New Joiner" incentives, as churn is highest in early tenure.

Product Bundling: Since "Competitors" are the main threat, bundling Online Security (which shows low churn) could act as a "sticky" feature to keep customers.

Geographic Targeting: Uttar Pradesh and Haryana show the highest churn volume, suggesting a need for regional-specific promotions or service quality audits.
