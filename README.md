# Airline-booking-analysis-
Data cleaning and analysis of airline booking records with an interactive dashboard for customer insights and booking trends.
## 📌 Project Overview

This project analyzes airline booking data to understand customer
behavior, booking preferences, and conversion patterns.\
A Power BI / Excel dashboard was created to visualize the data, track
KPIs, and provide insights for decision-making.

Dataset size: **50,000 rows × 18 columns**

------------------------------------------------------------------------

## 🛠 Data Cleaning Steps

The dataset underwent cleaning and preprocessing before analysis: 1.
**Standardized categorical values**\
- Converted `yes/no` fields to consistent format (Yes, No).\
- Unified booking status (`Complete`, `Abandoned`).

2.  **Handled time columns**
    -   Converted `flight_hour` to numeric hour (`hours` column).
3.  **Checked missing values**
    -   No missing values were found (100% complete dataset).
4.  **Converted datatypes**
    -   Converted `purchase_lead`, `length_of_stay`, `flight_duration`
        to numeric formats.
5.  **Prepared flags**
    -   `meal_flag`, `conversion_flag` set as binary indicators (0/1).

------------------------------------------------------------------------

## 📊 Key Insights from Dashboard

-   **Bookings Completed:** 7,478 confirmed bookings.\
-   **Average Flight Duration:** 437 minutes.\
-   **Average Length of Stay:** 23 days.\
-   **Average Passengers per Booking:** 2.

### Conversion Analysis

-   Internet channel conversion: **15%**\
-   Mobile channel conversion: **11%**

### Service Preferences

-   79% of customers requested extra services (meals, baggage, preferred
    seat).

### Meal Preferences by Flight Hour

-   Peak meal requests occur between **6 AM - 12 PM**.

### Booking Trends

-   Highest booking volume observed on **Monday and Wednesday**.\
-   **Circle Trips** booked earlier in advance (\~95 days) compared to
    **Round Trips (\~85 days)**.

### Geographic Insights

-   Major booking origins: India, New Zealand, China, USA, Russia.

------------------------------------------------------------------------

## 🚀 How to Use

1.  Open the dataset `customer_booking_Analysis.xlsx` in Excel / Power
    BI.\
2.  Use the pre-built pivot tables & dashboard to explore:
    -   Conversion rates\
    -   Service preferences\
    -   Booking trends\
    -   Geographic distribution

------------------------------------------------------------------------

## 📂 Files in Repository

-   `customer_booking_Analysis.xlsx` → Raw dataset + Pivot tables +
    Dashboard.\
-   `Airline Booking Analysis Dashboard.png` → Snapshot of the
    dashboard.\
-   `README.md` → Project documentation (this file).

------------------------------------------------------------------------

## ✅ Conclusion

The analysis provides actionable insights into customer booking
behavior, preferred services, and sales channel effectiveness.\
This can help airlines optimize marketing strategies, improve conversion
rates, and enhance customer satisfaction.
