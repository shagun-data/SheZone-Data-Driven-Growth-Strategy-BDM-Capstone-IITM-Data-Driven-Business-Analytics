# SheZone Salon: Data-Driven Business Analytics & Retention Strategy

A comprehensive business analytics and customer segmentation project for **SheZone Salon** (Lucknow Cantt), analyzing transaction patterns, customer churn, and competitive positioning to drive data-backed growth strategies.

---

## 📌 Executive Summary

SheZone Salon is a mid-sized women’s beauty parlour operating in Topkhana, Lucknow Cantt since 2015. Offering core services across haircare, skincare, nail care, and bridal makeup, the salon enjoys a strong local presence. However, recent operational trends revealed two primary business bottlenecks: **rising customer churn** and **steep off-season revenue contractions** (particularly during May–June following peak wedding season in April).

This project integrates primary transactional data with secondary competitor intelligence to evaluate revenue drivers, quantify churn risks, and propose tech-enabled, personalized retention strategies.

---

## 🏬 Field Visit & Stakeholder Engagement

<p align="center">
  <img width="1014" height="552" alt="ME WITH THE OWNER OF THE SALON" src="https://github.com/user-attachments/assets/18b562f2-bca5-446a-b3b3-db0b5ec03372" />
  <br>
  <em>Fig 1: Primary data collection and stakeholder discussion on-site at SheZone Salon.</em>
</p>

---

## 📊 Datasets & Methodology

The analysis relies on two primary data streams:

1. **Primary Transactional Dataset (Jan–Jun 2025):** 
   * **Size:** 450 consolidated appointment logs over 6 months.
   * **Variables:** `CustomerID`, `Service Type`, `Visit Date`, `Booking Channel` (Walk-in vs. Appointment), `Discounts`, `Final Bill Value`.
   * **Key Observation:** Active customer footfall dropped by **28%** between January (peak) and June (trough), with bill values displaying strong right-skewness due to high-value, low-frequency premium packages.

2. **Secondary Competitor Benchmark Data:**
   * **Size:** 300 records compiled across competitor brand portals and aggregator platforms (UrbanClap, Justdial) for players like Lakmé Salon and Naturals.
   * **Key Observation:** Premium market competitors leverage advanced skincare diagnostics and structured loyalty programs to command higher average transaction values (~₹3,100) and sustain brand stickiness.

---

## 🔍 Analytical Framework & Insights

* **Descriptive & Seasonal Profiling:** Verified an overall **8–10% month-on-month revenue decline** during non-festive quarters (April to May/June).
* **RFM (Recency, Frequency, Monetary) Segmentation:** 
  * **Champions (20%)** & **Loyal (30%):** Core revenue generators; primary focus for referral incentives.
  * **At-Risk (24%)** & **Need Action (26%):** Highly vulnerable to churn; prioritized for targeted win-back campaigns.
* **ABC Revenue Analysis:**
  * **Category A (Volume Drivers):** Routine grooming services (Haircuts, Waxing, Threading) generate **70% of total footfall**.
  * **Category B/C (Margin Drivers):** Premium services (Bridal Packages, Hair Spas) account for **>40% of total revenue** despite lower booking frequency.

---

## 🚀 Key Recommendations & Future Scope

1. **Tech-Enabled Personalization:** Implement AI-driven skin consultation tools to bridge the service gap with premium market alternatives.
2. **Dynamic Loyalty Programs:** Structure automated reminders and custom discounts aimed directly at the **At-Risk (24%)** customer segment before complete churn occurs.
3. **Off-Season Promotional Bundles:** Create service packages pairing routine high-frequency treatments with premium add-ons to stabilize revenue through May and June.

---

## 🛠️ Tech Stack & Tools Used
* **Data Processing & Analysis:** Python (Pandas, NumPy) / Excel
* **Customer Analytics:** RFM Modeling, ABC Analysis
* **Visualization:** Matplotlib / Seaborn
