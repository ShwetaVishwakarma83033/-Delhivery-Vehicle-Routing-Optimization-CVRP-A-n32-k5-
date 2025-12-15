# -Delhivery-Vehicle-Routing-Optimization-CVRP-A-n32-k5-
# 🚚 Delhivery Vehicle Routing Optimization (CVRP)

<p align="center">
  <img src="assets/banner.png" alt="Vehicle Routing Optimization Banner" width="100%">
</p>

## 📌 Project Overview
This project solves a **Capacitated Vehicle Routing Problem (CVRP)** using  
**Python and Google OR-Tools** to optimize logistics routing, similar to real-world  
**Delhivery hub-to-hub and mid-mile transportation networks**.

The objective is to:
- Minimize total transportation distance  
- Respect vehicle capacity constraints  
- Improve fleet utilization  
- Provide actionable insights for supply chain network design  

---

## 🎯 Business Problem
Logistics companies face high operational costs due to:
- Inefficient route planning  
- Underutilized vehicles  
- Poor load distribution  
- Network scalability challenges  

This project demonstrates how **data-driven optimization** can significantly reduce cost  
and improve operational efficiency.

---

## 🧠 Dataset Details
- **Source:** TSPLIB  
- **Instance:** A-n32-k5  
- **Nodes:** 32 (1 depot + 31 customers)  
- **Vehicles:** 5  
- **Vehicle Capacity:** 100 units  

---


---

## ⚙️ Methodology

### 1️⃣ Data Preparation
- Parsed TSPLIB `.vrp` file
- Extracted node coordinates, demand, and depot
- Created Euclidean distance matrix

### 2️⃣ Exploratory Data Analysis (EDA)
- Node distribution visualization
- Demand distribution analysis
- Capacity feasibility check

### 3️⃣ Optimization Model (CVRP)
- OR-Tools `RoutingModel`
- Distance callback
- Demand callback
- Vehicle capacity constraints
- Guided Local Search optimization

### 4️⃣ Solution & KPIs
- Optimized vehicle routes
- Route distance calculation
- Vehicle load & utilization
- Fleet-level performance metrics

---

## 📊 Key KPIs & Results

| Metric | Value |
|------|------|
| Total Demand | 410 |
| Fleet Capacity | 500 |
| Fleet Utilization | ~82% |
| Vehicles Used | 5 |
| Distance Reduction | ~40–60% |

---

## 🗺️ Optimized Routes Visualization

<p align="center">
  <img src="outputs/route_visual.png" alt="Optimized Routes" width="80%">
</p>

---

## 📈 Business Insights
- Existing fleet is sufficient to handle projected demand  
- Optimized routing significantly reduces transportation distance  
- Balanced vehicle utilization improves operational efficiency  
- Route clustering indicates potential micro-hub opportunities  

---

## 🛠️ Tech Stack

| Category | Tools |
|--------|------|
| Programming | Python |
| Optimization | Google OR-Tools |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Dataset | TSPLIB |

---

## 🚀 How to Run the Project

```bash
pip install ortools pandas numpy matplotlib

## Run  the notebook
notebook/Delhivary.ipynb

```html
<img src="assets/banner.png" width="100%">
