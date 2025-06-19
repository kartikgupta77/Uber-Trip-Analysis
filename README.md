# Uber-Trip-Analysis
 🚕 Uber Trip Analysis using Power BI

This Power BI project analyzes Uber trip data to generate actionable insights into ride patterns, booking behavior, and operational efficiency. The analysis is structured into three dashboards: *Overview Analysis, **Time Analysis, and **Details Tab*.

---

 📌 Business Objective

To provide stakeholders with clear insights into booking trends, revenue patterns, and trip efficiency, enabling data-driven decisions to optimize operations and improve customer satisfaction.

---

 📊 Dashboard 1: Overview Analysis

🎯 Key Performance Indicators (KPIs)

- *Total Bookings* – Total number of trips.
- *Total Booking Value* – Total revenue generated.
- *Average Booking Value* – Revenue per booking.
- *Total Trip Distance* – Combined distance of all trips.
- *Average Trip Distance* – Average distance traveled per trip.
- *Average Trip Time* – Average trip duration.

✅ Business Outcomes

- Identify trends in ride bookings and revenue.
- Evaluate trip efficiency (distance and time).
- Compare key performance indicators (KPIs) across time periods.
- Gain insights to optimize pricing and resource allocation.

---

📈 Visualizations & Features

- *Measure Selector (Disconnected Table)*:
  - Toggle between metrics like Total Bookings, Booking Value, and Trip Distance.
  - Visuals update dynamically based on selected measure.

- *Category Breakdown*:
  - Bookings segmented by *Payment Type* (Card, Cash, Wallet, etc.).
  - Analysis by *Trip Type* (Day/Night).

- *Dynamic Chart Titles*:
  - Automatically update based on selected metric.

- *Slicers*:
  - Interactive filters for *Date, **City*, and other dimensions.

- *Tooltips*:
  - Provide additional metrics like average distance when hovering.

- *Vehicle Type Grid*:
  - Matrix showing KPIs across vehicle types.
  - Includes conditional formatting, sorting, and filtering.

- *Trend Visualization*:
  - Bookings by day to highlight peak/off-peak periods and special events.

---

📍 Location-Based Analysis

### Key Insights

- *Most Frequent Pickup Points* – Optimize driver deployment.
- *Most Frequent Drop-off Points* – Analyze destinations and demand.
- *Farthest Trip* – Investigate outlier trips and long-distance behaviors.
- *Top 5 Booking Locations* – Identify high-demand zones.
- *Preferred Vehicle Types by Location* – Match vehicle availability with local demand patterns.

---

⏰ Dashboard 2: Time Analysis

Analyze ride demand patterns across various time intervals for smarter scheduling and pricing strategies.

🧠 Dynamic Measure Selector

- Global selector to switch between:
  - Total Bookings
  - Total Booking Value
  - Total Trip Distance

> All time-based charts update according to the selected metric.

Time-Based Visuals

- *Pickup Time (10-Min Intervals)*:
  - Area chart for detecting minute-level trends.

- *Day of Week*:
  - Line chart to analyze weekday vs weekend activity.

- *Hour vs Day Heatmap*:
  - *Rows*: Hour of Day (0–23)
  - *Columns*: Day of Week (Mon–Sun)
  - *Values*: Selected KPI
  - Identify busiest times of day and week.

---

🧾 Dashboard 3: Details Tab

Features

- *Grid Table View*:
  - Full trip-level dataset with filtering options.

- *Drill-Through Functionality*:
  - Right-click on visuals to access detailed records for any data point.

- *Bookmark Toggle*:
  - Switch between filtered and full datasets with a single click.

---

🔄 Data & Refresh Details

- *Source: Uber trip dataset *(not included in repository).
- *Refresh Frequency*: To be configured based on data source setup.
- *Implementation*: Built using native Power BI visuals and custom DAX measures.

---

🚀 Project Setup

> Ensure the dataset is available and correctly formatted before proceeding.

1. Import the Uber trip dataset into Power BI.
2. Build and validate the data model with necessary relationships.
3. Create dynamic DAX measures and KPIs.
4. Implement all dashboards and visualizations as described.
5. Add bookmarks, slicers, and export/download options for better interactivity.

---
