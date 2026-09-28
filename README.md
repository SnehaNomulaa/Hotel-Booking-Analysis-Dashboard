# Hotel Booking Analysis & Interactive Dashboard

An end-to-end hotel booking analytics project that transforms reservation-level data into an interactive Power BI dashboard for analyzing booking demand, cancellation behaviour, pricing, stay duration, and customer and property patterns.

## 📌 Project Overview

Hotels generate a large volume of reservation data, but booking volume alone does not explain business performance.

This project analyzes hotel reservation data to understand:

- Booking demand and booking patterns
- Cancellation behaviour and demand stability
- Pricing and stay-duration patterns
- Customer and market segment behaviour
- Hotel and geographical booking patterns
- Booking value-related patterns

The project combines Python-based data preparation and analysis with an interactive Power BI dashboard.

## 🎯 Business Questions

The dashboard is designed around four key questions:

1. **Demand** — How many bookings are coming in, when do they occur, and where are they concentrated?
2. **Stability** — How much of that demand is cancelled, and which segments show greater cancellation risk?
3. **Value** — What pricing and stay-duration patterns are associated with bookings?
4. **Customer & Property Behaviour** — Which customer types, market segments, room types, meal choices, and cities are associated with different booking patterns?

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Excel
- Power BI
- Google Colab

## 🔄 Project Workflow

Raw Hotel Booking Data  
↓  
Python / Pandas Data Preparation  
↓  
Prepared Dataset  
↓  
Power BI Analysis  
↓  
Interactive Dashboard  
↓  
Business Insights

## 📊 Power BI Dashboard

### Booking Performance, Demand & Cancellation

![Hotel Booking Dashboard](hotel_booking_dashboard.png)

This page provides an executive view of:

- Booking volume
- Cancellation behaviour
- Monthly booking trends
- Booking concentration by city
- Hotel-wise bookings and cancellations
- ADR by city
- Cancellation rate by market segment

### Revenue & Customer Analysis

![Revenue and Customer Analysis](revenue_customer_analysis.png)

This page analyzes:

- Revenue-related booking value
- Customer type behaviour
- Average ADR by month
- Guest composition by hotel type
- Stay duration and ADR
- Revenue contribution by city

## 💡 Key Insights

- Booking volume should be evaluated together with cancellation and booking-value measures rather than in isolation.
- Cancellation behaviour varies across customer and market segments and should be investigated separately.
- City Hotel and Resort Hotel can exhibit different booking and cancellation patterns.
- Booking volume and monetary value represent different perspectives of performance.
- ADR should be interpreted together with stay duration; neither metric alone proves profitability.
- Customer type, market segment, room type, and meal choice help explain booking behaviour and value.
- City-level analysis helps identify differences in booking volume, ADR, cancellation, and value-related patterns.

## 📂 Project Files

- `Hotel_Booking_Data_Cleaning.ipynb` — Data cleaning and preparation notebook
- `Hotel_Booking_Reservation.pbix` — Power BI dashboard
- `Hotel_Booking_Reservation.xlsx` — Excel dataset
- `hotel_bookings_updated_2024.csv` — Dataset
- `hotel_booking_dashboard.png` — Dashboard screenshot
- `revenue_customer_analysis.png` — Revenue and customer analysis screenshot
- `Hotel_Booking_Dashboard_Project_Brief.pdf` — Project documentation

## 👩‍💻 Author

**Sneha Nomula**

Computer Science and Engineering  
Artificial Intelligence & Machine Learning
