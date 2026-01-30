Here’s a clean, professional **GitHub README.md–ready** version using proper Markdown structure, emojis, headers, lists, inline math formatting, and code blocks where appropriate.

---

# 🚚 FleetOps Intelligence: Real-Time Logistics Performance Dashboard

## 📌 Project Overview

This project focuses on the **design and implementation of an end-to-end Operations Intelligence Dashboard** for a logistics fleet (*Forte Freight / Operation D2D*).

The system consolidates fragmented operational and financial data spanning **multiple years (2021–2024)** to provide visibility into:

* Fleet efficiency
* Revenue yield per asset
* Operational and delay-driven bottlenecks

By digitizing truck movements, mileage performance, and delay metrics, the dashboard establishes a **single source of truth** for fleet managers—enabling optimization of high-value assets and reduction of costly **“grounded” time**.

---

## 🚀 Key Features

### 🚛 Fleet Performance Tracking

* Real-time monitoring of truck status:

  * **Active**
  * **Stationary**
  * **Grounded**
* Live location and ignition status updates per vehicle

### 📈 Mileage vs. Revenue Correlation

* Comparative analysis of **planned vs. actual mileage**
* Daily/Monthly mileage benchmark:

  * **Target:** `450 km/day`
* Direct linkage between mileage performance and revenue yield

### ⏱️ Advanced Delay Analytics

* Dedicated delay tracker with root-cause categorization:

  * **Internal:** Finance, Workshop
  * **External:** Border, Loading, Documentation
* Enables rapid identification of efficiency leaks

### 📊 Multi-Year Financial Trend Analysis

* Year-to-date (YTD) revenue and profitability tracking
* Cross-year comparison for:

  * **2021**
  * **2022**
  * **2023**
  * **2024**

### 🧑‍💼 Responsible Party Attribution

* Automated assignment of delay accountability to:

  * Logistics
  * Finance
  * Workshop
* Supports structured performance reviews and corrective actions

---

## 🛠️ Technical Implementation

### 🔧 Data Engineering

* Cleaned and normalized **20+ disparate CSV and Excel datasets**
* Integrated data sources include:

  * Truck telemetry
  * Fuel consumption logs
  * Revenue and invoicing reports

### 📐 KPI Modeling

Key performance metrics implemented include:

```text
MTD Mileage Performance (%) =
(Actual Mileage / MTD Plan) × 100
```

```text
Revenue Variance =
Actual Revenue − Target Revenue
```

```text
Cumulative Delay Duration =
Total downtime (hours/days) by delay category
```

* Mechanical vs. documentation-related downtime tracked independently

### 🧰 Tooling Stack

* **Python / Pandas** – data cleaning and transformation
* **Power BI / Tableau** – dashboard design and visualization
* **Advanced Excel** – Power Query, Pivot Tables, VBA (where applicable)

---

## 📊 Insights Delivered

### 🔍 Identifying “Profit Leaks”

* Analysis revealed that:

  * **Border Clearance** and **External Documentation delays**
  * Accounted for **40%+ of non-productive time** in early 2024

### 🔄 Vehicle Lifecycle Management

* Tracked individual truck IDs (e.g., *KCG series*)
* Identified recurring mechanical failure patterns
* Enabled data-backed maintenance scheduling decisions

### ⚙️ Operational Efficiency Gains

* Introduced **Mileage Difference (MTD)** metric
* Clearly highlighted:

  * Underperforming trucks
  * Drivers requiring intervention
* Supported consistent achievement of the **450 km/day target**

---

## 📂 Project Structure

```bash
├── data/
│   ├── mileage/
│   ├── revenue/
│   └── delay_trackers/
│
├── visualizations/
│   ├── dashboard_screenshots/
│   └── interactive_files/
│
├── scripts/
│   ├── data_cleaning/
│   └── transformations/
│
└── README.md
```

---

## ✅ Outcome

This project demonstrates a clear shift from **reactive logistics management** to **data-driven operational excellence**, empowering decision-makers with real-time insights, accountability, and performance optimization tools.

---

If you want, I can:

* Add **screenshots embedding syntax**
* Optimize this for **recruiters / portfolio visibility**
* Tailor it for **Power BI vs Tableau**
* Add a **Tech Stack badge section** or **KPIs-at-a-glance table**


| Executive Summary (Home) | Fleet Report (Overview) | Workshop Report | Revenue Tracker | Client Tracker |
| --- | --- | --- | --- | --- |
| ![Executive Summary](https://github.com/SteveJoe-cloud/Excel-Logistics-Projects/blob/main/assets/Exec%20Summary-%20Operations%20Dashboard.png) | ![Fleet Report](https://github.com/SteveJoe-cloud/Excel-Logistics-Projects/blob/main/assets/Fleet%20report-%20Operations%20Dashboard.png) | ![Workshop report](https://github.com/SteveJoe-cloud/Excel-Logistics-Projects/blob/main/assets/Workshop%20report-%20Operations%20Dashboard.png) | ![Revenue Tracker](https://github.com/SteveJoe-cloud/Excel-Logistics-Projects/blob/main/assets/Revenue%20Tracker-%20Operations%20Dashboard.png) | ![Client Tracker](https://github.com/SteveJoe-cloud/Excel-Logistics-Projects/blob/main/assets/Client%20Tracker-%20Operations%20Dashboard.png) |






