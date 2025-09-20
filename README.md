# Airline-Flight-Data-Analysis
To analyze airline flight data for patterns in pricing, flight frequency, and duration across multiple carriers. To identify key performance indicators (KPIs) and trends that influence operational efficiency and customer demand. To generate actionable insights for optimizing pricing strategies, route planning, and service offerings.
The key points are:

- View Dataset <a href="https://github.com/shahlarafiq12/Airline-Flight-Data-Analysis/blob/main/airlines_flights_data.csv">Dataset</a>
- View Analysis <a href="https://github.com/shahlarafiq12/Airline-Flight-Data-Analysis/blob/main/Airline_flight_data_Analysis.ipynb">Airline Analysis</a>

## 1️⃣ Data Quality & Preparation
-	Removed unnecessary columns and duplicates, and checked for missing values to ensure data accuracy.
-	Identified and handled outliers such as unusually short/long flight durations and extreme price values.

## 2️⃣ Airline Distribution & Flight Frequency
-	Multiple airlines are represented, with some carriers dominating the dataset.
-	Top Airlines by Flight Count: A few airlines account for the majority of flights, while smaller carriers represent a minor share (<10%).
-	Horizontal bar charts highlighted that low-frequency airlines make up less than 5–7% of total flights.

## 3️⃣ Price Analysis
-	Price Range: Flights vary from low-cost options (≈₹1,100) to premium fares (>₹1,20,000).
-	Average Price by Airline: Some premium airlines consistently charge 25–30% higher fares compared to budget carriers.
-	Class Impact: Business and First-Class fares are 2–3× higher on average than Economy fares.

## 4️⃣ Flight Duration & Routes
-	Most flights cluster around 2–3 hours, with a few outliers beyond 10 hours.
-	Longer flights correspond to higher prices, but some anomalies suggest competitive pricing strategies on certain routes.

## 5️⃣ Peak Times & Demand Patterns
-	Certain airlines dominate specific time slots or routes, influencing ticket pricing.
-	Flight frequencies peak during holiday periods and weekends, indicating seasonal demand trends.

# 📈 Key Performance Indicators (KPIs)
1.	Flight Volume by Airline (%) – Share of total flights per airline (e.g., Top 3 airlines cover ~70–75%).
2.	Average Ticket Price by Class & Airline (₹) – Monitor cost differences across segments.
3.	Revenue Contribution by Airline (%) – Estimated based on flight frequency × average fare.
4.	Average Flight Duration (hours) – Evaluate operational efficiency and scheduling.
5.	Load Factor Proxy (Demand Pattern) – Use frequency trends as an indicator of route demand.
6.	Peak Demand Windows (%) – Measure percentage of flights during high-demand periods to optimize pricing strategies.

# 📌 Strategic Insights
-	Route Optimization: Focus on profitable routes dominated by top airlines to maintain market share.
-	Dynamic Pricing: Leverage demand trends to adjust fares during peak and off-peak periods.
-	Expand Budget Offerings: Lower-tier airlines and economy classes remain price-sensitive segments with growth potential.
-	Customer Segmentation: Tailor offers for premium travelers while retaining cost-conscious customers.


