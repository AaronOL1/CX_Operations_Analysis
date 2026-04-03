# 📊 Excel Data Processing Methodology

Since this project focuses on rapid prototyping and agile business intelligence, the entire ETL and modeling process is handled natively within **Advanced Excel**.

### Phase 1: Data Cleaning & Profiling
* **Format:** Converted raw CSV data into an Excel Table structure (`Ctrl+T`) for dynamic array scaling.
* **Null Handling:** Identified missing values in `Arrival Delay in Minutes` and applied logical imputation (replaced with 0 where correlated with no departure delay).

### Phase 2: Feature Engineering (Logical Formulas)
Created new calculated columns to map business logic:
* `Wait_Time_Status`: `IF` statements to flag operational delays exceeding acceptable thresholds.
* `Average_Service_Score`: Aggregating specific touchpoint scores (0-5) to create a single "Delivery Quality" proxy.

### Phase 3: Aggregation & Dashboarding
* Pivot Tables deployed to cross-reference `Satisfaction` against operational bottlenecks.
* Design of an executive Dashboard for rapid decision-making.