 # 📊 E-Commerce Orders & Logistics Performance Dashboard

An interactive analytical dashboard built in **Google Looker Studio** (formerly Data Studio) utilizing transactional retail orders data across the United States. The report tracks multi-year sales trends, shipping logistics, geographic volume distribution, and customer segment contributions.

🔗 **[View Live Interactive Dashboard](https://datastudio.google.com/reporting/34577d1c-75fc-4cb3-9018-94155d2a17ad)**  

---

## 📸 Dashboard Preview

![Orders Dashboard Preview](images/dashboard_preview.png)

> **Static Export:** A complete single-page export is available under [`docs/orders_dashboard.pdf`](docs/orders_dashboard.pdf).

---

## 📌 Executive Summary & Key Metrics

The underlying dataset tracks retail order fulfillment patterns and customer buying behaviors across 49 US States spanning 2014 to 2017:

| Metric | Value |
| :--- | :--- |
| **Total Line Items / Rows** | 9,994 |
| **Unique Orders** | 5,009 |
| **Unique Customers** | 793 |
| **Geographic Reach** | 49 US States (West, East, Central, South) |
| **Customer Segments** | Consumer, Corporate, Home Office |
| **Time Horizon** | 2014 – 2017 |

---

## 📈 Visualizations & Analytical Highlights

* **Multi-Year Order Volume Trajectory:** Evaluates year-over-year fulfillment activity across 2014, 2015, 2016, and 2017.
* **Monthly Seasonality:** Identifies transaction surges occurring throughout Q3 and Q4 (peaking in September and November), aligning with commercial procurement and retail holiday cycles.
* **Customer Segmentation:** Breakdown of order volume showing **Consumer** dominance (51.9%), followed by **Corporate** accounts (30.2%) and **Home Office** clients (17.8%).
* **Geographical Density:** Tracks top-performing metropolitan hubs by total order quantities, led by **New York City**, **Los Angeles**, **Seattle**, **San Francisco**, and **Philadelphia**.
* **Category Distribution:** Analyzes demand across core product categories (**Office Supplies**, **Furniture**, and **Technology**).
* **Fulfillment Logistics:** Monitors volume distribution across four primary delivery channels: *Standard Class*, *Second Class*, *First Class*, and *Same Day*.

---

## 🛠️ Tech Stack & Data Architecture

* **BI Platform:** Google Looker Studio
* **Data Source:** Microsoft Excel (`data/orders_dashboard_data_source.xlsx`)
* **Key Fields Analyzed:** `Order ID`, `Order Date`, `Ship Mode`, `Customer ID`, `Segment`, `City`, `State`, `Region`, `Category`, `Quantity`

---

## 📂 Repository Layout

```text
ecommerce-orders-analytics-dashboard/
│
├── data/
│   └── orders_dashboard_data_source.xlsx    # Source dataset
│
├── docs/
│   └── orders_dashboard.pdf                 # Exported PDF of the dashboard
│
├── images/
│   └── dashboard_preview.png                # Dashboard preview screenshot
│
├── .gitignore                               # Ignores OS & temporary Office files
└── README.md                                # Project documentation
