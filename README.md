# Coffee-Vending-Machine-Sales-Analysis

## Overview
This project analyzes one year of coffee vending machine transactions to understand which products drive revenue, when demand is highest, and how purchasing habits change over time. I used PostgreSQL to clean and explore the data, then built a Tableau dashboard that summarizes product performance, seasonality, peak purchase times, and payment behavior.

The result is a set of clear, actionable recommendations a vending operator could use to plan inventory, schedule maintenance around peak hours, and identify opportunities to improve revenue.

## Key Business Questions
- What is the total revenue per month?
- Which coffee type generates the most revenue?
- What are the top 5 selling products by quantity and revenue?
- How have sales trended over time?
- Which days of the week have the highest sales?
- What’s the peak hour of coffee purchases?
- Which payment method is most used — cash or card?

## Insights and Interpretation

### 1. Coffee Preferences

Milk-based drinks dominate: Latte, Americano with Milk, and Cappuccino contribute the largest share of revenue. Hot Chocolate also ranks highly, indicating non-coffee demand and supporting a broader product mix.


### 2. Day-of-Week Performance

Revenue is strongest on weekdays and weakest on Sunday, consistent with office traffic. This informs refill timing (e.g., stock up before Monday morning).

### 3. Peak Hours of the Day

Purchases peak in the morning (8–10 a.m.), with a smaller late-afternoon bump (~4 p.m.). This supports scheduling refills and maintenance outside peak windows to avoid lost sales.

### 4. Payment Method Preferences 

Card accounts for ~97% of transactions. Cash usage is minimal, which supports prioritizing digital payment reliability and reducing operational focus on cash handling.

### 5. Monthly Revenue

Monthly revenue is mostly stable with a few short spikes. These peaks would be worth investigating (e.g., location traffic, machine availability, or pricing changes) before making operational decisions.


## Recommendations 

- Prioritize inventory for top milk-based drinks + hot chocolate to reduce stock-outs.
- Schedule restocking before peak periods (especially weekdays mornings).
- Increase inventory/promotions during high-demand periods.
- Keep card payments highly reliable.


## Tableau Dashboard
The dashboard visualizes sales trends, peak hours, top products and revenue by month. It helps quickly identify patterns and support business decisions. 

https://public.tableau.com/app/profile/ana.vaz7019/viz/CofeeMachineAnalysis/Dashboard2?publish=yes

<img width="2838" height="1354" alt="Coffee_Dashboard" src="https://github.com/user-attachments/assets/09aa246c-634b-4906-aea0-a67484e317f5" />


## Tools & Technologies
- SQL: PostgreSQL for data analysis and querying
- Tableau: Data visualization and dashboard creation
