🚖 OLA Trips Data Analysis using SQL (Hive on Cloudera)
📄 Project Overview

This project analyzes the OLA Trips dataset, which contains detailed records of ride bookings made through OLA. The goal is to extract meaningful insights about customer behavior, cab category performance, trip costs, and overall profitability using SQL queries executed in Hive on Cloudera.

🧾 Dataset Description

The dataset includes the following key columns:

booking_id – Unique identifier for each ride

category – Type of OLA cab (Mini, Micro, Prime, Rentals, etc.)

gender – Gender of the customer

reason – Purpose of travel (Office, Personal, Airport, etc.)

day_of_week – Day on which the trip occurred

distance_travelled – Distance covered (in km)

total_trip_cost – Total fare amount paid by the customer

driver_base_cost, total_tax, toll – Cost components

ratings – Customer feedback rating (1–5 scale)

🎯 Objectives

Analyze revenue and profitability by cab category

Study customer trends by gender and travel purpose

Identify high-value and long-distance trips

Examine ratings and satisfaction patterns

Detect weekly or day-wise pricing trends

🧠 Operations Performed

Database and table creation in Hive

Data loading from CSV into Hive table

SQL queries for aggregation, grouping, and filtering

Revenue, cost, and profit analysis

Customer behavior and performance insights generation

🛠️ Technologies Used

Hive (SQL on Hadoop)

Cloudera Distribution for Hadoop (CDH)

HDFS for data storage

Excel/CSV for dataset preprocessing

📊 Key Insights

Rental and premium categories contribute maximum profit.

Friday shows the highest average trip cost due to surge pricing.

Office and corporate trips cover longer distances on average.

Male riders dominate most categories, while female riders prefer premium services.

🧩 Conclusion

Through SQL-based data analysis in Hive, this project uncovers patterns in OLA’s trip data that highlight operational efficiency, pricing trends, and customer satisfaction. The insights can help optimize pricing, improve driver performance, and enhance the overall ride experience.
