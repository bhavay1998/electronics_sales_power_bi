# Sales Dashboard: Electronics Retailer
Developing a sales [dashboard](sales_dashboard.pbix) for a consumer electronics retail business primarily situated in the US. The [dashboard](sales_dashboard.pbix) is meant to provide a high-level summary to help manage, optimize, and plan sales effectively through an interactive view of performance across time, products, customers, and geography.<br>
<br>
Project's aim is to implement core Power BI skills such as data modeling, visual design, filtering, and basic aggregation, without heavy use of DAX or Power Query.

## About the business
The revenue model of the retail business is transactional sales (i.e. quantity × unit price captured as sales).
Individual consumers of the business are distributed across multiple US states and cities in some other parts of the world such as China and India.

## About the data
The dataset used spans from January 2024 to December 2026. It is taken from [Data with Baara](https://www.datawithbaraa.com/wiki/power-bi#power-bi-welcome-to-course), website of [Baraa Khatib Salkini](https://www.youtube.com/@DataWithBaraa) - industry practitioner in the field of BI and data engineering. Two primary source files are used, namely, [cutomers.csv](source_data_preview/customers_preview.png) and [orders.csv](source_data_preview/orders_preview.png).

<p align="center">
  <img src="schema.png" alt="Schema" width="350"/>
</p>

The dataset comprises two tables: 
- `customers`: containing attributes such as geographic location, name and ID
-  `orders`: containing attributes such as product quantity, product name and order data 
