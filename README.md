
# Ola Bookings Analysis Dashboard

This project presents a **comprehensive Power BI dashboard** built on a dataset of **100,000 booking records** from Ola, one of the leading ride-hailing platforms in India. The primary objective of this project is to analyze customer behavior, driver performance, ride trends, cancellations, and overall platform efficiency through interactive data visualization.

## 📊 Dataset Overview

The dataset (`Bookings-100000-Rows.xlsx`) consists of **detailed booking information**, including:

* **Customer ID** and **Driver ID**
* **Booking Status** (Success, Cancelled by Driver, Cancelled by Customer, Incomplete)
* **Booking Date & Time** (weekday/weekend, match-day flags)
* **Fare, Charges, Discounts, Ratings**
* **Pickup and Drop Locations**
* **Cancellation Reasons**
* **Ride Duration and Distances**
* **CTAT (Customer Turnaround Time)** and **VTAT (Vendor Turnaround Time)** metrics

This data allows for an in-depth analysis of both the supply (drivers) and demand (customers) sides of the Ola ecosystem.

## 📈 Dashboard Highlights

The Power BI dashboard is designed to provide **key insights across multiple dimensions**:

1. **Overall Booking Performance**

   * Success rate of rides (kept above \~62%)
   * Cancellations by customers and drivers (maintained under 7% and 18% respectively)
   * Incomplete rides maintained under 6%

2. **Customer Behavior Analysis**

   * Top 5 customers with the highest number of successful rides
   * Patterns of ride booking during weekdays vs. weekends and match days
   * Impact of discounts and offers on customer booking frequency

3. **Driver Performance Analysis**

   * Top-performing drivers by ride completion and earnings
   * Driver cancellations vs. customer satisfaction ratings
   * Distribution of ratings across completed rides

4. **Revenue & Fare Insights**

   * Total revenue generated across successful rides
   * Average fare per ride
   * Effect of surge pricing and match-day demand on earnings

5. **Operational Efficiency**

   * Average **CTAT (Customer Turnaround Time)** and **VTAT (Vendor Turnaround Time)**
   * Ride completion trends across peak vs. non-peak hours
   * Booking distribution across different regions and locations

6. **Weekend & Match-Day Analysis**

   * Noticeable increase in bookings on weekends and during match days
   * Higher cancellation rates during peak traffic events
   * Revenue spikes aligned with special event days

## 🎯 Key Insights

* **Booking Success Rate**: \~62% overall, reflecting efficient ride completions.
* **Cancellations**: Customer cancellations <7% and driver cancellations <18%, indicating a healthy platform balance.
* **Customer Trends**: Higher engagement during weekends and match days, showing strong demand fluctuations.
* **Driver Performance**: A few drivers emerge as top performers with consistently high earnings and successful ride completions.
* **Revenue Growth**: Match days and weekends significantly boost overall revenue, highlighting event-driven demand surges.

## 🛠️ Tools & Technologies Used

* **Power BI**: For dashboard design, DAX measures, and interactive reporting
* **Excel**: For raw dataset management and cleaning
* **SQL-like Querying (via DAX)**: To calculate KPIs such as success rates, cancellations, and turnaround times

## 📌 Conclusion

This project demonstrates how **business intelligence tools like Power BI** can transform raw ride-booking data into meaningful insights that drive **strategic decision-making** for mobility companies like Ola. By analyzing **customer patterns, driver efficiency, revenue streams, and operational bottlenecks**, this dashboard provides actionable intelligence that can help in:

* Reducing cancellations
* Improving driver allocation
* Enhancing customer satisfaction
* Optimizing pricing strategies during peak demand
