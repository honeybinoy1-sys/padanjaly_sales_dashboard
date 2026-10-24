# padanjaly_sales_dashboard
A data cleaning and sales analysis project built on the WooCommerce orders of Jagadha by Padanjaly, an Ayurvedic products business. The raw order export was cleaned in Power Query and analysed in a Power BI dashboard to understand revenue, products, payments, customers and seasonality.

# Project Overview
Item	Detail
Source	WooCommerce orders export
Size	690 orders (one row per order), 72 columns
Period	January 2023 to May 2026
Currency	Orders recorded in USD and INR; all amounts converted to INR

# Dashboard
The dashboard contains:
KPI cards: Total Revenue, Total Orders, Guest Order %, Revenue in INR and Revenue in USD
Total Revenue and Total Orders by month
Total Revenue by payment method
Total Revenue by product
Total Orders by month

# Key Insights
Revenue: about ₹2.52M from 690 orders, roughly ₹3,650 per order.
Top product: Agnijith 90 gms brings in about half of revenue, and the wider Agnijith range around 80%.
Seasonality: orders peak in May and June and are lowest in September and October.
Busiest month: May 2026 had 83 orders, more than double any other month.
Highest revenue month: October 2025 (about ₹210k)
Payments: Razorpay accounts for 99.48% of revenue, cash on delivery for 0.52%.
International sales: USD orders (about $13K) make up close to 46% of revenue.
Guest checkout: 49.28% of orders are placed by guests

# Padanjaly_Location_dashboard
A data cleaning and analysis project built on the WooCommerce orders of Jagadha by Padanjaly, an Ayurvedic products business. The raw order export was cleaned in Power Query and analysed in a two-page Power BI report:
Sales Performance Dashboard: revenue, orders, products, payments and trends over time.
Location Analysis Dashboard: sales and customer behaviour by country, state and city.

# Visuals and KPI cards
Visual or card	What it shows
Revenue by billing country (filled map)	Which countries bring in revenue, shaded by amount
Billing city vs shipping city (donut)	How many orders ship to the billing city
Repeat customers by city	Which cities have customers who order again
Total orders by billing city	The cities with the most orders
Total units sold by billing state	Which states buy the most units
Cards: Countries Served, Same City %, Repeat Customers, Repeat Orders	Headline numbers linked to the visuals

# Location insights
Orders come from 24 countries, with India the darkest on the map.
98.84% of orders (682 of 690) ship to the billing city, and only 8 go to a different city.
21 repeat customers placed 48 orders, about 2.3 orders each. Hyderabad and Noida have the most repeat customers (3 each).
Bengaluru has the most orders (57), followed by Hyderabad (33), Thiruvananthapuram (28), Chennai (25), Mumbai (22) and Pune (17).
Order volume does not equal loyalty: Bengaluru has the most orders but only 2 repeat customers.
Tamil Nadu leads the units sold chart with about 100 units, more than double Telangana.

# Author
Honey Binoy
