# 🚚 Logistics & Transportation – Fleet Performance & Delivery Efficiency

### 📘 Project Overview
This Power BI project analyzes a logistics company’s fleet performance based on delivery efficiency, fuel usage, and operational cost metrics.  
It aims to identify improvement areas and optimize transportation routes and vehicle utilization.

---

### 🧩 Dataset Details
- **Trip_Data.csv**
  - Trip ID, Vehicle ID, Driver ID, Origin, Destination, Distance (km), Fuel Consumed, Delivery Status, Delivery Date.
- **Vehicle_Master.csv**
  - Vehicle ID, Vehicle Type, Capacity, Maintenance Cost.

---

### 🧹 1. Data Cleaning & Modeling (5 Marks)
- Replaced missing `Fuel Consumed` values with **average per Vehicle Type** using Power Query.
- Created relationship between `Trips` and `Vehicle Master` tables using `Vehicle ID (1:* )`.

---

### 📊 2. DAX Measures (5 Marks)
| Measure | Formula | Purpose |
|----------|----------|----------|
| **Fuel Efficiency** | `Distance / Fuel Consumed` | Analyze vehicle performance |
| **On-Time Delivery %** | `On-Time Trips / Total Trips` | Measure punctuality |
| **Cost per km** | `(Fuel Cost + Maintenance Cost) / Distance` | Evaluate operational cost |

---

### 📈 3. Visualizations (5 Marks)
| Visual | Description |
|---------|--------------|
| **Bar Chart** | On-Time Delivery % by Route |
| **Line Chart** | Fuel Efficiency trend by Month |
| **KPI Cards** | Avg. Delivery Time, Cost per km |
| **Map Visual** | Delivery performance by route (Origin → Destination) |

---

### 🧠 Insights & Findings
- Improved visibility on delivery delays and fuel efficiency.
- Identified underperforming routes and high-cost vehicles.
- Enabled data-driven decisions to reduce operational costs.

---

### 🧾 Files Included
| File | Description |
|------|--------------|
| `Logistics_Fleet_Performance.pbix` | Power BI report file |
| `Trip_Data.csv` / `Vehicle_Master.csv` | Raw datasets |
| `Trip_Data_Cleaned.csv` | Cleaned dataset |
| `Project_Report.pdf` | Project documentation and visuals |

---

📅 Author & Credits
Author: Sankar G

Location: Trichy

Year: 2025
