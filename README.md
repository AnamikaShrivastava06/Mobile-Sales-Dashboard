# Mobile-Sales-Dashboard: A Complete Walkthrough

I’m excited to share my Mobile Sales Dashboard—a project I built using Power BI to provide a holistic view of mobile phone sales across various regions, brands, and customer segments.


1. Executive Summary & Key KPIs

-Total Sales (₹769M): A high-level figure indicating the overall revenue generated from mobile phone sales.

-Total Quantity (19K Units): Shows the volume of devices sold, giving insight into market penetration.

-Total Transactions (4K): Reflects the number of purchase instances—helpful in understanding average basket size and repeat purchases.

-Average Price (₹40.11K): An important metric indicating the average selling price per unit, which can guide pricing and promotional strategies.


2. Time-Series Analysis (Monthly Trends)

Total Quantity by Month (Line Chart):

-This visual tracks monthly fluctuations, highlighting peak months (e.g., March and July) and potential seasonal dips (e.g., September).

-Identifies trends such as sales spikes during festival seasons or product launches.


3. Geographic Sales Distribution

Total Sales by City (Map Visual):

-A map of India with major cities (Delhi, Mumbai, Bangalore, Hyderabad, etc.) highlighted by sales volume.

-Bubble size or color intensity indicates which cities are top contributors.


4. Customer Ratings Analysis

Count of Customer Ratings (Bar Chart):

-Categorized as Good (2,331), Average (1,195), and Poor (309).

-Quickly shows overall satisfaction levels and areas needing improvement.


5.Payment Method Distribution

Transaction by Payment Method (Pie Chart):

-Breaks down usage of UPI, Debit Card, Credit Card, and Cash.

-Each slice represents a percentage share of total transactions.


6.Brand Performance & Comparison

Brand Table:

Apple: ₹161615730 in sales, 783 transactions, 3932 units

Samsung: ₹160038505 in sales, 775 transactions, 3923 units

OnePlus: ₹153719439 in sales, 712 transactions, 3830 units

Vivo: ₹150708428 in sales, 722 transactions, 3801 units

Xiaomi: ₹143753337 in sales, 743 transactions, 3664 units


7. Model-Level Insights

Total Sales by Mobile Model (Bar Chart):

iPhone SE: ₹60M

OnePlus Nord: ₹58M

Galaxy Note 20: ₹56M


8. Comparative Analysis & Filters

Slicers for Time Period & Brand:

-Monthly/Quarterly/Year-to-Date (MQYTD) Report or Same Period Last Year toggles.

-Filter by Brand, Payment Method, Mobile Model to drill into specific segments.


Technical Highlights

Data Modeling & ETL: Used Power Query to clean, transform, and merge data from multiple sources (e.g., Excel, CSV, SQL databases).

DAX Calculations: Created measures for dynamic aggregations, YTD comparisons, and rolling averages.

Visual Design: Employed user-friendly layout and color-coded visuals to simplify complex data.

Performance Optimization: Implemented hierarchies and data relationships for faster loading and smooth interactivity.
