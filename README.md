# 🛫 Customer Experience (CX) & Operations Optimization 

### 📌 Project Overview
This project focuses on analyzing the direct impact of operational bottlenecks on Customer Experience (CX) and brand loyalty. Using a comprehensive airline dataset, the goal is to identify root causes of customer dissatisfaction, specifically mapping how service delays and post-service engagement affect overall retention.

* **Objective:** To design a data-driven action plan that mitigates operational friction and improves the Net Promoter Score (NPS) proxy.
* **Core Focus:** Customer Journey mapping, Wait-time tolerance, and Post-service follow-up strategies.
* **Tools Used:** Advanced Excel (Data Cleaning, Feature Engineering, Pivot Tables, Dashboards).

### 🗂️ The Dataset
The dataset contains customer feedback and operational metrics, including:
* **Operational Variables:** Departure/Arrival delays (in minutes), Flight Distance.
* **CX Variables:** Ease of online booking, In-flight service, Leg-room service, Online support.
* **Target Variable:** Overall Satisfaction (Satisfied vs. Neutral/Dissatisfied).
* **Loyalty Metric:** Customer Type (Loyal vs. Disloyal Customer).

### 🚀 Key Executive Insights & Business Impact
Following the data manipulation and dashboarding phase, the following strategic insights were extracted for CX Operations:

1. **The Bottleneck Threshold (Critical Delay):** Wait-time analysis revealed that operational delays exceeding the **15-minute mark** act as a catalyst for churn. At this threshold, the satisfaction ratio entirely inverts, with dissatisfied customers outnumbering satisfied ones regardless of subsequent service recovery efforts.
2. **The Digital Friction (Microjourney Failure):** Pivot analysis demonstrated a false positive in service delivery. While physical execution (In-flight service) scored poorly among detractors (2.9/5), the actual root cause of churn originates in the digital planning phase. Dissatisfied customers reported critical friction in Booking, Check-in, and Online Support (averaging **2.7/5**).

### 🛠️ Execution & Methodology
* **ETL & Handling:** Raw data converted via Advanced Excel. Null values in arrival delays were logically imputed based on departure correlations to preserve CX feedback rows.
* **Feature Engineering:** Deployed logical `IF` statements to segment delay thresholds and `AVERAGE` models to group service variables into `Planning_Score` vs `Delivery_Score`.
* **Visualization:** Built an Executive Dashboard using 100% Stacked Column and Clustered Column PivotCharts to highlight friction gaps and wait-time impact.

---
*Status: 🟢 **Completed** - Dashboard and Executive Summary ready for presentation.*
