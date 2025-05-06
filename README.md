

Hotel Booking Demand Analysis Dashboard (Power BI + DAX + SQL + Excel)

markdown
 🏨 Hotel Booking Demand Analysis Dashboard | Power BI + DAX + SQL + Excel

This project presents a detailed Hotel Booking Demand Analysis Dashboard created using Power BI. The dashboard gives data-driven insights into hotel booking trends, customer behavior, seasonal demands, cancellations, and much more. It empowers stakeholders to make smarter decisions in managing resources, pricing, and guest satisfaction.

> This project is designed for hoteliers, data analysts, and travel platforms who want to understand the key drivers behind hotel booking patterns and optimize their operations accordingly.

---

 🎯 Objectives

- Identify booking trends across hotel types and time periods.
- Analyze cancellation patterns and their root causes.
- Compare performance between city and resort hotels.
- Understand guest preferences and lead time behavior.
- Enable data-driven decision making for hotel management.


 🛠️ Tools & Technologies Used

| Tool           | Purpose                                       |
|----------------|-----------------------------------------------|
| Power BI   | Data visualization & dashboard building       |
| DAX        | Custom KPIs, metrics & logic building         |
| SQL        | Data filtering and transformation             |
| Excel      | Initial data cleaning and formatting          |



📈 Key Dashboard Features

- 📅 Yearly, Monthly, and Daily Booking Trends
- 🏨 Hotel Type Comparison: City Hotel vs Resort Hotel
- 🔍 Cancellation Analysis: Patterns and percentages
- 🌐 Lead Time Analysis: Time between booking and arrival
- 👨‍👩‍👧‍👦 Guest Demographics: Adults, children, and babies
- 📊 Revenue and ADR Trends: Average Daily Rate and revenue metrics
- 🗃️ Dynamic Filters: Date, Hotel Type, Market Segment, and more

 🧮 Sample DAX Measures

Some important custom DAX measures used:

DAX
Total Bookings = COUNT(Bookings[Booking_ID])
Cancellation Rate = DIVIDE(CALCULATE(COUNT(Bookings[IsCanceled]), Bookings[IsCanceled] = 1), [Total Bookings])
Average Daily Rate = AVERAGE(Bookings[ADR])
Lead Time = AVERAGE(Bookings[LeadTime])


These formulas power key performance indicators and visualizations throughout the dashboard.

 🧼 Data Cleaning & Preparation

1. Raw Data (CSV/XLSX) imported into Excel.
2. Cleaned for missing values, inconsistent date formats, and invalid entries.
3. Loaded into Power BI using SQL queries and Power Query for advanced transformations.
4. Built DAX measures and relationships for dashboard KPIs.


 📊 Dashboard Preview

[Dashboard Preview](https://github.com/VaibhavDA893/assests/blob/main/Screenshot%202025-05-02%20170958.png)

This visual shows a consolidated view of all booking analytics, built using slicers, cards, line charts, bar graphs, and more.



- Hotel chains analyzing booking behavior and optimizing revenue.
-Business analysts evaluating seasonality and pricing strategies.
- Data science learners showcasing real-world projects using Power BI.
-Travel startups benchmarking customer trends and hotel categories.


