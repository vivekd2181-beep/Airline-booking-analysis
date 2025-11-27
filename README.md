# ✈️ Airline Booking Analysis Using Python & Seaborn



This project aims to perform a comprehensive **exploratory data analysis (EDA)** on an airline customer booking dataset. The goal is to uncover trends and patterns related to **trip types, booking preferences, extra services, and completion behavior** using Python and visualizations.

---

## 📌 Objectives

- Understand how customers interact with various booking channels.
- Explore the relationship between number of passengers and demand for extra baggage.
- Analyze booking behavior across different trip types: OneWay, RoundTrip, CircleTrip.
- Examine preferences for in-flight meals and baggage based on country of origin.
- Perform **univariate**, **bivariate**, and **multivariate analysis** to extract meaningful insights.
- Build visualizations to support business decision-making and user segmentation.

---

## 🗂️ Dataset Overview

The dataset contains airline customer booking data with the following relevant columns:

| Column Name             | Description                                          |
|-------------------------|------------------------------------------------------|
| `num_passengers`        | Number of passengers in a single booking             |
| `trip_type`             | Type of trip - OneWay, RoundTrip, CircleTrip         |
| `sales_channel`         | Channel used to book (Internet or Mobile)            |
| `booking_origin`        | Country from where the booking was made              |
| `wants_extra_baggage`   | Whether the customer opted for extra baggage (0/1)   |
| `wants_in_flight_meals` | Whether in-flight meals were requested (0/1)         |
| `booking_complete`      | Whether the booking was completed (0/1)              |

---

## 🧪 Analysis Breakdown

### ✅ 1. Univariate Analysis
- Distribution of trip types
- Sales channel preferences
- Extra baggage and in-flight meal demand
- Booking completion counts

### ✅ 2. Bivariate Analysis
- **Number of passengers vs Extra Baggage**
- **Sales Channel vs Trip Type**
- Observed that:
  - Internet is the dominant sales channel.
  - Passengers traveling in groups tend to request extra baggage more often.

### ✅ 3. Multivariate Analysis
- **Trip Type vs Sales Channel vs Extra Baggage**
- **Country of Origin vs Meal Preference vs Booking Completion**
- Notable insight:
  - Passengers from Australia showed high completion and meal request rates.
  - CircleTrip travelers had a higher tendency to opt for baggage services.

---

## 📊 Tools & Libraries Used

- Python 🐍
- Pandas 🐼
- Seaborn 🎨
- Matplotlib 📈
- Jupyter / Kaggle Notebooks

---

## 📌 Key Insights

- **Internet is the preferred booking channel** regardless of trip type.
- **Extra baggage** is requested most by travelers in CircleTrips and large groups.
- **Booking completion** is higher in countries like Australia where meal preference is also higher.
- OneWay trips show a slightly lower preference for additional services.

---

## 📝 Conclusion

This EDA highlights customer behavior patterns that can guide:
- Marketing strategies (e.g. offer discounts for in-flight meals to countries with low uptake).
- Operational planning (e.g. expect higher baggage volume in CircleTrips).
- Sales optimizations (e.g. improve mobile booking experience).

---


