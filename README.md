.McDonald's - Restaurant Sales Analysis

1. Project Title (Description)
Restaurant Sales Performance Analysis Using Order and Menu Data
This project analyzes restaurant order and menu data to understand sales performance, customer behavior, and revenue trends across categories, time, and products.

2. Problem Statement
The restaurant generates large volumes of order data but lacks clear insights into:
Which menu categories and items generate the most revenue
Customer ordering patterns by time, day, and month
Sales differences between weekdays and weekends
Without analysis, decision-making for pricing, promotions, and inventory is inefficient.

3. Objectives (What We Achieve)
Analyze total revenue by menu category
Identify the most frequently ordered and highest-earning menu items
Study daily, monthly, and time-based order patterns
Compare weekday vs weekend sales
Provide data-driven recommendations for business growth

4. Dataset Overview
Dataset 1: Order Details (CSV)
order_id
order_date
order_time
item_id
Dataset 2: Menu Items (Excel)
menu_item_id
item_name
category
price
Both datasets were merged using item_id.

5. Tools and Techniques
Tools Used
Python
Pandas (data cleaning & analysis)
Techniques Applied
Data merging (JOIN)
GroupBy aggregation
Time-based analysis (hour, weekday, month)
Descriptive statistics

6. Formulas Used
Total Revenue = Σ Price
Orders per Day = Count of unique order_id per date
Average Items per Order = Total items ÷ Total orders
Category Revenue = Σ Price grouped by category
Top Items = Highest revenue or frequency count

7. Method (Steps to Solve)
1.Imported both datasets
2.Cleaned date and time fields
3.Merged order and menu data
4.Created derived columns (month, weekday, hour)
5.Applied aggregation functions
6.Compared trends across categories and time
7.Interpreted insights and business impact

8. Key Findings
🔹 Revenue by Category (Top Performers)
Burgers: ₹21,459.99 (highest)
Chicken: ₹12,283.45
Pasta: ₹9,147.14
🔹 Most Frequently Ordered Item
Big Mac
🔹 Total Revenue Generated
₹61,003.78
🔹 Average Items per Order
2.28 items per order
🔹 Peak Order Time
12 PM – 2 PM (Lunch hours)
🔹 Weekday vs Weekend Sales
Weekdays: ₹44,029.38
Weekends: ₹16,974.40
➡️ Higher sales on weekdays due to regular customer flow
🔹 Top 5 Menu Items by Revenue
1.Meatball Marinara
2.Quarter Pounder with Cheese
3.Angus Third Pounder
4.Bulgogi Burger
5.Big Mac

9. What We Accomplished
Identified top-performing categories and products
Discovered peak business hours
Understood customer ordering behavior
Provided actionable insights for management

10. Limitations
No customer demographic data
No promotional or discount information
Data limited to a single time period

11. Future Opportunities
Add customer segmentation analysis
Analyze impact of discounts and offers
Predict future sales using machine learning
Optimize inventory using demand forecasting

12. Recommendations
Promote Burger and Chicken categories aggressively
Launch combo offers during lunch hours
Introduce weekend-specific deals to boost sales
Focus inventory planning on top 5 items

13. Conclusion
This project successfully transformed raw restaurant data into meaningful business insights. The analysis revealed strong product categories, peak ordering times, and sales patterns that can directly support strategic decisions, revenue growth, and customer satisfaction.


