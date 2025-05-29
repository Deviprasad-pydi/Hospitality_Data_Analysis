# 🏨 AtliQ Hotels Data Analysis Project

## 📊 Overview

AtliQ Hotels is a prestigious luxury hotel chain operating in India, with properties in major cities such as Mumbai, Delhi, Hyderabad, and Bangalore. This project involves a comprehensive data analysis of the hotel's performance from **May 2022 to August 2022** to uncover business insights and recommend strategies to improve revenue, market share, and customer satisfaction.

## 🚩 Problem Statement

AtliQ Grands is currently facing challenges due to declining **revenue** and **market share**. The goal of this project is to analyze key business metrics to identify patterns, address inefficiencies, and provide actionable strategies for recovery and growth.

## 🛠 Tools Used

- Python
  - Pandas
  - Seaborn
  - Matplotlib
- Jupyter Notebook

## 📁 Project Structure


## 📦 [Datasets](https://github.com/Deviprasad-pydi/Hospitality_Data_Analysis/tree/Datasets)

  - `dim_hotel.csv`
  - `dim_room_type.csv`
  - `dim_customer.csv`
  - `fact_bookings.csv`
  - `fact_aggregated_bookings.csv`
  - `new_data_august.csv`

> 💡 The datasets contain ~135,000 records for analysis.

## 📌 Project Steps

### 1. Data Import & Exploration
- Loading data using Pandas.
- Initial exploratory data analysis(EDA) to understand the schema and content.

### 2. Data Cleaning
- Handling missing values.
- Standardizing formats and data types.
- Validating data consistency.

### 3. Data Transformation
- Merging dimension and fact tables.
- Creating derived features.
- Aggregating data for insight extraction.

### 4. Insight Extraction
- Booking and revenue analysis by city, room type, and month.
- Guest behavior by channel and season.
- Expense distribution and profitability.

## 🔍 Key Insights

- **Room Types**:
  - RT2 (Elite) is most preferred, especially in Mumbai.
  - RT4 (Presidential) sees the lowest demand.
  
- **City Performance**:
  - Delhi has the highest occupancy rate at 61.61%.
  - Bangalore lags with 56.59%.

- **Temporal Trends**:
  - Weekend occupancy is significantly higher (72.39%) than weekdays (50.90%).
  - Revenue peaks in July, May, and June.

- **Customer Satisfaction**:
  - Delhi tops guest satisfaction with a rating of 3.79.

- **Booking Channels**:
  - Indirect platforms (e.g., makemytrip, others) dominate the booking source.

## 📈 Recommendations

### 🏨 Room Type Strategy
- Introduce bundled packages (e.g., breakfast, spa).
- Offer revenue-boosting add-ons like late check-outs.

### 📍 City-Specific Approaches
- Address booking barriers (e.g., pricing).
- Partner with tech companies for corporate deals.

### 📅 Temporal Optimization
- Promote work-from-hotel packages.
- Host seasonal events for better weekend utilization.

### 📊 Booking & Revenue
- Encourage direct bookings via exclusive perks.
- Improve website UX and mobile experience.

### 💰 Expense & Profitability
- Offer ancillary services (spa, dining, tours).
- Utilize off-peak periods for conferences/events.

## 🏁 Conclusion

This project demonstrates how structured data analysis can drive strategic business decisions in the hospitality industry. Through insights derived from customer behavior, operational metrics, and financial data, AtliQ Hotels can position itself more competitively and improve both guest satisfaction and revenue growth.

