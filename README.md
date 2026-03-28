# Supply Chain Analytics — FMCG Domain (AtliQ Mart)

> *Diagnosing delivery failures before expansion — tracking On-Time, In-Full, and OTIF performance to restore customer trust and fix service gaps.*

---

## Overview

This project addresses a **critical supply chain issue** at **AtliQ Mart** — a growing FMCG company operating across 3 cities in Gujarat, India, with plans to expand to major cities within the next 2 years.

Key customers were **not renewing contracts** due to poor delivery service — orders were arriving late, incomplete, or both. Management needed visibility into delivery performance to identify failures fast and fix them before the planned expansion.

The goal of this project is to build a **metrics-driven supply chain dashboard** that tracks delivery reliability, surfaces root causes, and provides actionable insights to improve service quality.

---

## Problem Statement

| Issue | Impact |
|---|---|
| Orders delivered **late** | Customers unable to plan inventory |
| Orders delivered **incomplete** | Stockouts and revenue loss for customers |
| Key customers **not renewing contracts** | Direct revenue and relationship loss |
| Expansion plans at risk | Service quality must be proven before scaling |

> Management required an immediate, trackable solution — a dashboard focused on **On-Time %, In-Full %, and OTIF %** to catch issues early and course-correct in real time.

---

## Objectives

- Calculate all required **supply chain KPIs** from raw order and delivery data
- Build an **interactive dashboard** aligned with stakeholder requirements
- Track **delivery performance** across cities, customers, and product categories
- Identify patterns behind **Early, On-Time, and Delayed deliveries**
- Surface **additional insights** beyond the initial requirements

---

## Core Metrics

### Primary KPIs

| Metric | Definition |
|---|---|
| **OT % (On-Time)** | % of orders delivered on or before the agreed delivery date |
| **IF % (In-Full)** | % of orders delivered with the full quantity requested |
| **OTIF % (On-Time In-Full)** | % of orders that were both on time AND in full — the strictest measure of delivery reliability |

### Supporting Metrics

| Metric | Definition |
|---|---|
| **LIFR % (Line Fill Rate)** | % of order lines delivered in full |
| **VOFR % (Volume Fill Rate)** | % of total ordered volume actually delivered |
| **Total Orders** | Count of all customer orders placed |

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and interactive visualization |
| **SQL** |
| **DAX** | KPI calculation — OT %, IF %, OTIF %, and supporting metrics |
| **Data Modeling** | Relationships between orders, deliveries, customers, and products |

---

## Key Insights

### Overall Delivery Performance
- **OTIF % is significantly below target** across all cities — meaning most orders fail on at least one of the two dimensions
- On-Time % and In-Full % both fall short of agreed service levels, indicating a **systemic issue** rather than isolated incidents

### City-Level Analysis
- Performance varies meaningfully across the 3 cities — some locations show consistently worse delivery reliability
- City-level gaps suggest **logistics and warehouse capacity** issues that are location-specific

### Customer-Level Analysis
- Certain customers show **disproportionately low OTIF %** — directly mapping to the non-renewals reported by management
- High-value customers with the worst service scores represent the **highest churn risk** ahead of expansion

### Product & Category Analysis
- Some product categories show **higher In-Full failures** — pointing to supply planning or forecasting gaps
- Frequently short-delivered products are likely candidates for **safety stock review**

### Trend Analysis
- Daily and weekly patterns reveal whether performance is **improving, worsening, or stagnant**
- No clear improvement trend detected — highlighting the urgency of corrective action before city expansion

---

## Data Model

![Data Model](https://github.com/user-attachments/assets/5e352e29-27e3-4cdf-a6ed-0e828d82b4d8)

---

## Dashboard Preview

### Orders at a Glance
![Orders at a Glance](https://github.com/user-attachments/assets/ccb288e5-c20e-48fc-9002-ee5ebce84cde)

### Service Level Analysis
![Service Level Analysis](https://github.com/user-attachments/assets/38913a90-7e89-4adc-b2ef-752153e8d679)

### Order Lines at a Glance
![Order Lines at a Glance](https://github.com/user-attachments/assets/8dfc5b78-0f8d-4ed8-9bda-9bc5978ee8d4)

### Products at a Glance
![Products at a Glance](https://github.com/user-attachments/assets/87c710d1-f02d-484a-85eb-0de1275aac3b)

---

## Connect

If you found this project useful or have suggestions, feel free to open an **Issue** or submit a **Pull Request**.
