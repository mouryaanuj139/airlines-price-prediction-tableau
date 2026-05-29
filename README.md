# ✈️ Airlines Price Prediction Analysis

An interactive Tableau dashboard analyzing **Indian domestic airline pricing patterns** across 6 airlines, 6 cities, and multiple routes — helping users understand how ticket prices vary by airline, class, departure time, stops, and days before departure.

---

## 🔗 Live Dashboard
👉 [View on Tableau Public](https://public.tableau.com/app/profile/anuj.mourya4186/viz/AirlinesPricePredictionAnalysis_17795418257320/Dashboard1)

---

## 📸 Dashboard Preview


<img width="1290" height="530" alt="Dashboard 1" src="https://github.com/user-attachments/assets/387dbd7d-2305-48a3-a697-a01e93036c40" />

---

## 🎯 Objective

To explore and visualize the key factors that influence flight ticket pricing in India, enabling travelers and analysts to identify the **cheapest airlines**, **best booking windows**, and **optimal routes**.

---

## 📊 Key Dashboards & Sheets

| Sheet Name | Description |
|---|---|
| **Dashboard 1** | Main interactive overview with filters for airline, class, source city, and days before departure |
| **Price_Vary_with_Airlines** | Compares average ticket prices across all 6 airlines |
| **Highest / Lowest Avg Airline** | Highlights the most and least expensive carrier |
| **Price variation b/w Business & Economy** | Side-by-side class price comparison |
| **Daysleft / Price** | How prices change as departure date approaches |
| **Last Minute Premium** | % price surge for last-minute bookings vs. early booking |
| **Departure_time vs Price** | Ticket cost by time of day for departure |
| **Arrival_time vs Price** | Ticket cost by time of day for arrival |
| **Busiest Route** | Most-traveled source–destination city pairs |
| **Price change with change in source and destination** | Route-level price variation across 6 cities |
| **Average Economy Price** | Average economy class fare benchmarks |
| **Total Flights** | Volume of flights per airline/route |

---

## 🛠️ Interactive Parameters

The dashboard includes 4 dynamic filters that update all visuals in real time:

- **Select Airline** — Air India, AirAsia, GO FIRST, Indigo, SpiceJet, Vistara
- **Select Class** — Business / Economy
- **Select Source City** — Bangalore, Chennai, Delhi, Hyderabad, Kolkata, Mumbai
- **Days Before Departure** — Slider from 1 to 49 days

---

## 💡 Key Insights

- 📈 **Prices surge significantly** in the last 2–3 days before departure (captured via the *Last Minute Premium* metric)
- 💼 **Business class fares** are substantially higher than Economy, with the gap varying by airline
- 🕐 **Departure and arrival time** has a measurable impact on ticket pricing
- 🏆 **Vistara** tends to have the highest average fares; **AirAsia / SpiceJet** are among the lowest
- 🛤️ Route matters — prices vary considerably based on source and destination city pairs

---

## 📁 Dataset

| Field | Description |
|---|---|
| `airline` | Airline name (6 carriers) |
| `flight` | Flight number |
| `source_city` | Departure city |
| `destination_city` | Arrival city |
| `departure_time` | Time of day for departure |
| `arrival_time` | Time of day for arrival |
| `stops` | Number of stops (non-stop / 1 stop / 2+ stops) |
| `class` | Travel class (Economy / Business) |
| `duration` | Flight duration in hours |
| `days_left` | Days remaining before departure |
| `price` | Ticket price (INR) |

- **Source:** Clean_Dataset (Excel) — 10,000 records
- **Tool:** Tableau Desktop 2025.2

---

## 🔧 Custom Calculations Built

- `Average Price Per Airline` — FIXED LOD expression per airline
- `Lowest / Highest Avg Airline` — Dynamic label for cheapest/most expensive carrier
- `Last Minute Premium` — % difference between prices at 2 days vs. 15 days before departure
- `Total Flights`, `Total Airlines`, `Total Routes` — Summary KPI metrics
- `Average Economy Rate` — Class-filtered average price

---

## 📂 Repository Structure

```
📁 airlines-price-prediction-tableau/
├── 📊 Airlines_Price_Prediction_Analysis.twbx   ← Tableau packaged workbook
├── 📄 README.md                                  ← You are here
└── 📁 screenshots/                               ← dashboard screenshots here
    ├── dashboard_overview.png
    └── price_by_airline.png
```

---

## 🚀 How to Open

1. Download `Airlines_Price_Prediction_Analysis.twbx`
2. Open with **Tableau Desktop** (2021.1 or later) or **Tableau Public Desktop** (free)
3. Use the parameter controls to explore pricing by airline, class, city, and booking window

---

## 👤 Author

**[Anuj Mourya]**
[LinkedIn](https://www.linkedin.com/in/anujmourya/) • [Tableau Public](https://public.tableau.com/app/profile/anuj.mourya4186/vizzes)
