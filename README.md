# Retail_Sales_Intelligence

Retail Sales Intelligence
Interactive Power BI Dashboard & Analytics

Description

This repository features an end-to-end business intelligence solution designed to analyze four years of United States domestic retail sales. By processing over 1,480 individual transaction records, this project transforms raw data into an interactive Power BI dashboard. The analysis exposes the hidden realities behind headline revenue figures—identifying true profitability drivers, pinpointing margin-draining discount thresholds, and evaluating supply chain compliance to empower data-driven commercial decisions.

Tech Stack
Business Intelligence: Microsoft Power BI

Data Extraction & Transformation (ETL): Power Query (M Formula Language) for cleaning text inconsistencies, imputing missing values, and shaping the data model.

Calculations & Logic: DAX (Data Analysis Expressions) for creating dynamic KPIs, rolling averages, and custom measures (e.g., Net Profit Margin, Z-score anomaly detection).

Source Data & Prototyping: Microsoft Excel (Sourced verbatim from Sale combined (Autosaved)_2.xlsx, specifically referencing the original layout and logic prototyped on the Dashboard sheet).

Project Goals
Uncover True Profitability: Move beyond top-line revenue to identify which specific product categories, regions, and customer segments actively generate net profit versus those that operate at a loss.

Optimize Discounting Strategies: Evaluate the financial impact of current promotional tiers to prevent structural margin leakage.

Monitor Supply Chain Efficiency: Track shipping carrier performance and costs against promised Service Level Agreements (SLAs).

Enable Self-Service Analytics: Provide stakeholders with a dynamic, filterable interface to explore seasonal trends, geographic performance, and customer value without needing technical expertise.

Key Questions Answered by the Dashboard

1. Which product categories are our true profit engines?
Technology is the undisputed profit engine. It generated $1,016,245 in sales and returned a massive $162,882 in net profit, maintaining the highest profit margin across the business at 16.03%.

On the opposite end, Furniture may look good on the top line with $923,673 in sales, but it yielded a meager $25,054 in net profit—an incredibly thin 2.71% margin. Office Supplies sits in the middle with a healthy 14.33% margin.

2. At what threshold do discounts begin to destroy value?
The data reveals a stark threshold effect where excessive discounting flips margins from positive to negative:

0% - 5% Discounts: Generates an average profit of $251.68 per order.

5% - 10% Discounts: Profitability halves to an average of $124.75 per order.

>15% Discounts: This is the breaking point. Orders with discounts exceeding 15% completely destroy value, resulting in an average loss of $481.04 per transaction.

3. Are premium shipping services delivering on their promises?
No, they are consistently falling short.

Express Air (the premium expedited option) averages a 2.01-day delivery time, missing standard 1-day expectations.

Oddly, Delivery Truck is currently the fastest fulfillment method, averaging 1.88 days, though it is significantly more expensive per order (averaging $45.81 compared to Express Air's $8.97).

Regular Air offers the best balance for non-expedited goods, delivering in 2.21 days for just $7.52.

4. Who are our most valuable customers versus our most costly?
Revenue does not equal profitability when it comes to your customer base.

The Most Valuable: Andy Reiter is your top client. Across just 5 orders, he generated $29,701 in sales but yielded an exceptional $14,328 in net profit. He is followed closely by John Stevenson ($12,628 profit) and Jack O'Briant ($11,664 profit).

The Most Costly: Clay Cheatham is the single most costly customer; a single order of $21,134 resulted in a net loss of -$4,266. Maribeth Dona is also a significant liability, actively draining -$3,617 in profit despite generating over $36,000 in top-line revenue.

5. How is our sales performance distributed geographically?
Performance is heavily concentrated, meaning the business has significant geographic risk tied to just a few states. The top three markets account for over 21% of all total revenue:

California: $216,367 in sales ($24,857 profit)

Florida: $185,151 in sales ($24,528 profit)

New York: $164,906 in sales ($19,741 profit)
