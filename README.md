# 🚆 Indian Railways Network Analysis: Connectivity & Efficiency

## 📌 Overview
Exploratory Data Analysis on the Indian Railways operational dataset containing 
186,124 records across 12 columns, covering 11,000+ trains and 8,000+ stations.

The goal is to understand how traffic and connectivity are distributed across 
the network — and whether the system is balanced or heavily centralized around 
a few critical nodes.

---

## 📊 Key Findings
- 🔴 Just **2,777 out of 8,000+ stations** account for **80% of total network traffic**
- 🏙️ **CST-Mumbai** is the busiest station with **1,027 unique trains**
- 📏 Median route distance is just **82 km** but the longest route (CAPE–DBRG) covers **4,260 km**
- ⏰ Peak train activity occurs at **08:00** for both arrivals and departures
- 🚉 Most frequent route: **Chennai Beach → Tambaram** with **137 trains**
- 🔁 Traffic flows are **bidirectional** — Howrah Junction and Sealdah dominate both origins and destinations
- ⚡ Average route efficiency: **20.28 km per stop**

---

## 📁 Analysis Sections
1. Data Loading and Overview
2. Data Cleaning & Preprocessing
3. Busiest Railway Stations
4. Train Route Structure Analysis
5. Train Route Distance Analysis
6. Station Connectivity Analysis
7. Source–Destination Route Analysis
8. Scheduling Pattern Analysis
9. Distance vs Stops Relationship
10. Critical Railway Hubs & Network Dependence
11. Route Efficiency Analysis
12. Station Hub Classification
13. Station Role Analysis
14. Key Insights & Conclusion

---

## 🛠️ Tech Stack
| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading, cleaning, analysis |
| Matplotlib | Bar charts, pie charts, line plots |
| Seaborn | Histograms, scatter plots |
| Jupyter Notebook | Development environment |

---

## 📂 Project Structure
indian-railways-network-analysis/
│
├── data/
│   └── Train_details_22122017.csv
│
└── notebooks/
└── 01_eda.ipynb

---

## 📋 Dataset
- **Records:** 186,124
- **Columns:** 12 (Train No, Train Name, Station Code, Station Name, Arrival Time, Departure Time, Distance, Source Station, Destination Station, etc.)
- **Source:** Indian Railways operational data (December 2017)

---

## 👤 Author
**Martin George**  
B.Tech Student  
📧 Email: 06martingeorge@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/martin-george-635340321/
