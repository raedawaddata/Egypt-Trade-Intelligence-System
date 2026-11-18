# 🇪🇬 Egypt Trade Intelligence System (2018–2024)
**End-to-End Bilateral Trade Analytics, Forensic Mirror Audit & Enterprise Data Warehouse**

> 🎓 **DIGILIANS Graduation Project** — Ministry of Communications and Information Technology (MCIT) | *Professional Data Analyst Track*  
> 🚀 **[Launch Live Interactive Dashboard](https://raedawaddata.github.io/Egypt-Trade-Intelligence-System/)**

---

## 📌 Executive Summary
This enterprise analytics solution transforms raw UN Comtrade bilateral trade registries (2018–2024) into actionable economic and customs intelligence. By reconciling origin vs. destination declarations, engineering a Kimball Galaxy Data Warehouse in MS SQL Server, and deploying a 5-page executive BI suite, the system uncovers an **$81.3B bilateral mirror trade discrepancy** and evaluates Egypt's export competitiveness across **3,227 HS-6 commodities**.

---

## 📊 Executive Dashboard Showcase

### 1. Executive Overview & Macroeconomic Trajectory
![Executive Overview](Executive%20Overview.png)

### 2. Strategic Competitiveness & Balassa RSCA Quadrants
![Competitiveness & RSCA](Competitiveness%20%26%20RSCA.png)

### 3. Product-Market Opportunity Scoring Engine
![Opportunity Scoring](Opportunity%20Scoring.png)

### 4. Forensic Mirror Trade & Customs Risk Audit (What-If Simulator)
![Mirror Trade Audit](Mirror%20Trade%20Audit.png)

### 5. Regional Peer Benchmarking (Egypt vs. Morocco, Saudi Arabia & Vietnam)
![Regional Benchmark](Regional%20Benchmark.png)

---

## 🏗️ End-to-End Data Engineering Pipeline

| Phase | Layer | Architecture & Deliverables |
| :--- | :--- | :--- |
| **Phase 1** | **Data Ingestion** | Python, UN Comtrade API v1, 251 Parquet files; resolved `'World'` double-counting trap (`$89.69B` → `$44.85B`, achieving **99.0% alignment** with official CAPMAS figures). |
| **Phase 2** | **Forensic & Economic Models** | Dual-Threshold Mirror Risk Engine (`+$145B` Under-Invoicing/High-Seas risk, `+$20B` normal freight, `-$84B` transit hubs), Balassa **RCA & RSCA** index, and 0–100 Opportunity Scoring. |
| **Phase 3** | **Enterprise Data Warehouse** | **MS SQL Server 2022** · Kimball Galaxy Schema (`3 Dimensions`, `2 Fact Tables`, `1,927,472 rows`, `5 Pre-computed SQL Views`). |
| **Phase 4** | **Business Intelligence** | 5-page executive report with dynamic DAX measures, cross-filtering, slicers, and What-If sensitivity analysis. |

---

## 🔍 Key Analytical Findings
* **Macroeconomic Trajectory (2018–2024):** Total exports reached **$272.28B** (+7.3% CAGR), while non-oil exports achieved uninterrupted growth of **+74.2%** ($21.65B to $37.71B), reaching an all-time structural share of **84.1%** of total exports in 2024.
* **Forensic Mirror Audit ($81.28B Gap):** Partners reported **$353.56B** CIF imports from Egypt vs. **$272.28B** FOB reported by Egypt—highlighting high-seas petroleum re-routing anomalies such as refined fuel oil (HS `271012`) to Saudi Arabia (`+$4.61B` product gap).
* **Export Champions (Balassa RCA & RSCA):** Identified **160 Current Winners** and **1,265 Niche Winners** across 3,227 commodities, led by Non-monetary Gold (`710812`), Refined Petroleum (`271012`), Urea Fertilizers (`310210`), Refined Copper Wire (`740811`), and Fresh Citrus (`080510`).

---

## 🛠️ Technology Stack
`Python` · `UN Comtrade API` · `MS SQL Server` · `Data Warehousing` · `Power BI` · `DAX`

---

## 👥 Project Team
* **Raed Awad**
* **Ehab Shahat**
* **Mohammed Fuaad**
* **Mahmoud Ezzat**
