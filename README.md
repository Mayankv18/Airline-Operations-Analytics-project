# ✈️ Airline Operations & Performance Analytics | Tableau

An end-to-end **Airline Operations Analytics Dashboard** built using **Tableau** to analyze flight activity, airline performance, delays, cancellations, operational issues, outliers, and delay patterns.

The project transforms raw flight data into an interactive set of dashboards designed to provide **management-level operational insights** and support data-driven decision-making.

---

## 📌 Project Overview

Airline operations generate large amounts of data related to flights, routes, airlines, delays, cancellations, and operational factors.

This project analyzes that data through Tableau to answer key business questions such as:

- Which months have the highest flight activity?
- Which airports are the busiest origin hubs?
- Which destinations receive the most flights?
- Which airlines have the highest flight volume?
- Which airlines experience the highest arrival and departure delays?
- Which airline records the most cancellations?
- What are the major causes of flight delays?
- Which origins have the highest arrival-delay risk?
- Does flight distance have an impact on arrival delay?
- Which flights are extreme delay outliers?
- Which airline has the most variable delay pattern?
- How do delays change across years and months?

---

# 🎯 Business Objective

The primary objective of this project is to provide a **360° view of airline operational performance** using interactive Tableau dashboards.

The analysis focuses on five major areas:

1. **Flight Volume & Network Activity**
2. **Airline Performance**
3. **Delay Drivers & Operational Risk**
4. **Distance, Delay & Outlier Analysis**
5. **Delay Distribution & Time-Based Trends**

---

# 📊 Dashboard Structure

The project contains **5 interactive Tableau dashboards**.

---

## 1️⃣ Dashboard 1 — Flight Operations Overview

<img width="1913" height="1043" alt="Image" src="https://github.com/user-attachments/assets/89e4257b-cdb1-412d-8c74-80c222a254e7" />

### Focus
Understanding overall flight volume, airline presence, origin hubs, destinations, and yearly activity.

### Key KPIs

- **Total Flights:** 200
- **Number of Airlines:** 8
- **Number of Origin Hubs:** 8

### Key Insights

- **February** records the highest monthly flight volume with **23 flights**.
- **BOM** is the busiest departure hub with **31 flights**.
- **JAI** is the most frequent destination with **36 flights**.
- **AeroVista** leads airline flight volume with **33 flights**.
- **2023** records the highest flight activity with **85 flights**.

### Visualizations

- Monthly Flight Volume
- Flights by Origin Hub
- Flight Activity by Year
- Top Flight Destinations
- Flight Volume by Airline

---

## 2️⃣ Dashboard 2 — Airline Performance Analytics

<img width="1917" height="1043" alt="Image" src="https://github.com/user-attachments/assets/f60ceac3-9e9d-4e49-bcac-ed730f9f7ba1" />

### Focus
Comparing airlines based on arrival delays, departure delays, cancellations, and overall performance.

### Key KPIs

| KPI | Value |
|---|---:|
| Average Arrival Delay | 68.44 min |
| Average Departure Delay | 52.66 min |
| Cancelled Flights | 24 |

### Key Insights

- **StarAir** records the highest average arrival delay at **92.38 minutes**.
- **StarAir** also records the highest average departure delay at **71.88 minutes**.
- **StarAir** has the highest number of cancellations with **6 flights**.
- StarAir emerges as the **weakest overall performer** based on the performance score.

### Visualizations

- Average Arrival Delay by Airline
- Average Departure Delay by Airline
- Cancellations by Airline
- Airline Performance Treemap

---

## 3️⃣ Dashboard 3 — Delay & Operational Risk Analysis

<img width="1917" height="1032" alt="Image" src="https://github.com/user-attachments/assets/048ea9d1-bb78-4516-a114-f9b942691f83" />

### Focus
Identifying the operational factors responsible for delays and determining high-risk airlines and origins.

### Key Insights

- **Carrier-related issues** contribute the largest total delay: **3,442 minutes**.
- **NAS** contributes **3,029 minutes** of total delay.
- **Weather** contributes **2,291 minutes**.
- **JetConnect** records the highest carrier delay at **618 minutes**.
- **CloudAir** has the highest weather-related delay at **403 minutes**.
- **PNQ** records the highest average arrival delay at **92.28 minutes**.

### Visualizations

- Delay by Cancellation/Delay Reason
- Carrier Delay by Airline
- Weather Impact by Airline
- Total Delay by Operational Factor
- Arrival Delay Risk by Origin

---

## 4️⃣ Dashboard 4 — Distance, Delay & Outlier Analysis

<img width="1917" height="1032" alt="Image" src="https://github.com/user-attachments/assets/77e572ce-4070-460b-a15e-eec7028688cf" />

### Focus
Analyzing the relationship between flight distance and arrival delay while identifying extreme delay flights and airline-level variability.

### Key Insights

- Flight distance shows **limited impact on average arrival delay**.
- Extreme delays are concentrated in a small number of flights.
- Flight **FL10104** records an extreme arrival delay of **325 minutes**.
- Flight **FL10183** records an extreme arrival delay of **324 minutes**.
- **StarAir** shows the highest delay variability with a standard deviation of approximately **93.06 minutes**.

### Visualizations

- Flight Distance vs Arrival Delay
- Extreme Delay Outlier Analysis
- Distance–Delay Pattern by Airline
- Delay Variability by Airline

---

## 5️⃣ Dashboard 5 — Delay Distribution & Time Analysis

<img width="1917" height="1038" alt="Image" src="https://github.com/user-attachments/assets/d01208d4-df9d-477f-9cf5-af560ddd9de3" />

### Focus
Understanding the distribution of delays and identifying delay patterns across years, airlines, and months.

### Key Insights

- Most flights experience relatively **short delays**.
- Extreme delays occur less frequently but represent significant operational risk.
- **2024** records the highest average arrival delay at approximately **75.66 minutes**.
- **StarAir** remains one of the most consistently high-delay airlines across the analyzed years.
- **May** emerges as the most delay-prone month, with an average arrival delay of approximately **95.05 minutes**.
- **May–June** shows a noticeable period of elevated delay levels.

### Visualizations

- Arrival Delay Distribution
- Extreme Delay Distribution
- Average Arrival Delay by Year
- Airline Delay Trends Across Years
- Monthly Average Arrival Delay

---

# 🎨 Dashboard Design

The dashboards use a consistent visual language to make important insights easy to identify.

### Color Strategy

| Color | Meaning |
|---|---|
| 🟦 Teal | Normal / standard performance |
| 🟧 Orange | Highest value / key insight |
| 🔴 Red | Critical / extreme issue |
| 🔵 Navy | Titles, trends & supporting elements |

The use of **orange as an accent color** helps management quickly identify the most important value in each visualization.

---

# 🛠️ Tools & Technologies

- **Tableau** — Data visualization & dashboard development
- **Microsoft Excel** — Dataset preparation
- **Data Analytics** — Exploratory and comparative analysis
- **Calculated Fields** — KPI and performance calculations
- **Parameters & Filters** — Interactive analysis
- **Dashboard Actions** — User interaction and exploration

---

# 📈 Analytical Techniques Used

The project uses several analytical techniques including:

- Descriptive Analytics
- Comparative Analysis
- Trend Analysis
- Distribution Analysis
- Outlier Detection
- Delay Risk Analysis
- Airline Performance Benchmarking
- Correlation/Relationship Analysis
- KPI Analysis

---

# 🔍 Key Business Findings

The overall analysis highlights several operational areas that require attention:

### 1. Airline Performance

**StarAir** consistently appears as a weaker-performing airline based on arrival delays, departure delays, cancellations, and delay variability.

### 2. Delay Drivers

**Carrier-related issues** represent the largest contributor to total delay minutes, followed by NAS and weather-related factors.

### 3. High-Risk Locations

**PNQ** has the highest average arrival delay among the analyzed origin hubs.

### 4. Extreme Events

A small number of flights experience exceptionally high delays, with extreme delays exceeding **300 minutes**.

### 5. Seasonal Pattern

**May** represents a significant delay-risk period, recording the highest average monthly arrival delay.

### 6. Distance vs Delay

The analysis suggests that **flight distance alone does not strongly explain arrival delays**, indicating that operational factors may play a more important role.

---

# 💼 Management Recommendations

Based on the analysis, airline management can consider the following actions:

### ✈️ 1. Improve StarAir Performance

Conduct a root-cause analysis of StarAir's:

- Arrival delays
- Departure delays
- Cancellations
- Delay variability

### 🔧 2. Address Carrier-Related Delays

Since carrier issues represent the largest delay contributor, management should investigate:

- Aircraft turnaround processes
- Crew availability
- Ground operations
- Maintenance scheduling
- Boarding and departure processes

### 🌦️ 3. Prepare for Weather Disruptions

Strengthen operational planning during periods with higher weather-related delays.

### 📍 4. Focus on High-Risk Origins

PNQ and other high-delay origins should receive additional operational monitoring.

### 📅 5. Prepare for Seasonal Delay Peaks

May–June should be analyzed for:

- Capacity constraints
- Aircraft utilization
- Crew scheduling
- Airport congestion
- Weather conditions

### 🚨 6. Monitor Extreme Delay Flights

Create an operational alert system for flights crossing predefined delay thresholds, such as:

- 120+ minutes → High Risk
- 180+ minutes → Critical
- 300+ minutes → Extreme

---

# 📂 Project Structure

```text
Airline-Operations-Analytics/
│
├── Dataset/
│   └── airline_flight_dataset.xlsx
│
├── Tableau/
│   └── Airline_Operations_Dashboard.twbx
│
├── Screenshots/
│   ├── dashboard_1_flight_operations.png
│   ├── dashboard_2_airline_performance.png
│   ├── dashboard_3_delay_risk.png
│   ├── dashboard_4_outlier_analysis.png
│   └── dashboard_5_delay_analysis.png
│
└── README.md
