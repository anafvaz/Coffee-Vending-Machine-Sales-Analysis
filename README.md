# Coffee-Vending-Machine-Sales-Analysis

## Overview
This project analyzes sales data from a coffee vending machine using PostgreSQL for data exploration and Tableau for visualization.
The goal was to clean the dataset, explore sales patterns, and answer key business questions that could help optimize pricing, inventory, and machine placement.

As a junior data analyst, I focused on practicing real-world SQL queries, creating clear visual insights, and improving my ability to turn raw transactional data into meaningful business decisions.

## Key Business Questions
- What is the total revenue per month?
- Which coffee type generates the most revenue?
- What are the top 5 selling products by quantity and revenue?
- What’s the average price per transaction?
- How have sales trended over time?
- Which days of the week have the highest sales?
- What’s the peak hour of coffee purchases?
- Which payment method is most used — cash or card?
- Who are the top 10 customers by total spend?

## Insights and Interpretation

### 1. Coffee Preferences

The data shows that Lattes were the most purchased drink, followed by Americanos with milk and Cappuccinos. These three coffee types generated most of the total revenue, which suggests that customers strongly prefer milk-based beverages over plain options. Hot Chocolate also appeared among the top sellers, indicating that the machine attracts both coffee and non-coffee drinkers.

If this were a real operation, ensuring consistent stock levels for milk-based drinks and Hot Chocolate would likely help maintain or increase revenue.

### 2. Monthly Revenue Patterns

The machine generated a total of ₴115,431 over the period analyzed. Monthly revenue remained fairly stable overall, but there were noticeable increases during winter months. These spikes likely relate to colder weather or higher customer activity during the holiday and early spring seasons.

This trend indicates that sales are somewhat seasonal, and revenue could be maximized by running promotions or increasing stock during colder months.

### 3. Day-of-Week Performance

Sales were highest on Fridays and Mondays, with Sundays showing the lowest activity. This pattern aligns with typical workplace behavior, where customers tend to purchase coffee at the start and end of the workweek.

This finding suggests that the vending machine is likely located in or near an office environment. Regular refills and machine maintenance should be scheduled before Monday mornings and Friday afternoons to ensure product availability during peak demand.

### 4. Peak Hours of the Day

The busiest hours for sales were between 8:00 a.m. and 10:00 a.m., matching standard morning coffee habits. A smaller increase in activity was observed around 4:00 p.m., which likely corresponds to after-work or late-afternoon beverages, as customers seek a drink before leaving the office or heading home.

To avoid lost sales, restocking and maintenance should be done outside these key hours, especially in the early morning period.

### 5. Payment Method Preferences 

Card payments make up the vast majority of transactions. Cash is used only rarely. Card transactions also account for most of the total revenue. This indicates that customers overwhelmingly prefer digital payments at this vending machine.

### 6. Customer Behavior

The top ten customers accounted for a significant portion of total revenue. These individuals purchased more frequently and consistently than the average buyer, demonstrating a clear pattern of loyalty.

Implementing a simple rewards or loyalty system, such as discounts or free drinks after a certain number of purchases, could strengthen customer retention and drive repeat sales.

### 7. Average Transaction Value

The average transaction value was ₴31.75, suggesting that most customers buy a single beverage per visit.

Small promotional offers, such as bundle discounts could encourage higher spending per transaction without requiring major operational changes.

### 8. Overall Sales Trend

Sales data indicates a steady upward trend over time, suggesting that the vending machine has a growing base of regular customers and a stable location.

Expanding to similar locations or replicating the product mix in other machines could help sustain growth and improve overall profitability.

## Key Insights Summary
- Lattes, Americanos with milk, and Cappuccinos drive most revenue.
- Peak sales occur 8–10 a.m., with a smaller peak at 4 p.m.
- Card payments dominate transactions.
- Top 10 customers represent a large share of revenue.
- Monthly revenue peaks in colder months, showing seasonality.

## Tableau Dashboard
The dashboard visualizes sales trends, peak hours, top products and revenue by month. It helps quickly identify patterns and support business decisions. 

https://public.tableau.com/app/profile/ana.vaz7019/viz/CofeeMachineAnalysis/Dashboard1

<img width="2838" height="1406" alt="Dashboard 1 (1)" src="https://github.com/user-attachments/assets/10e31023-8617-4952-840d-01d4ab63fa3c" />

## Tools & Technologies
- SQL: PostgreSQL for data analysis and querying
- Tableau: Data visualization and dashboard creation
