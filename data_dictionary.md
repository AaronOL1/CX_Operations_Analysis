# 📖 Data Dictionary: Airline CX Operations

This document describes the structure and variables of the raw dataset used for the Customer Experience (CX) and Operations Analysis.

### 📌 Target & Demographics
* **satisfaction:** Overall satisfaction level (`satisfied` or `neutral/dissatisfied`). *Target variable.*
* **Customer Type:** Loyalty status (`Loyal Customer` or `disloyal Customer`).
* **Age:** Customer's age in years.
* **Type of Travel:** Purpose of the flight (`Personal Travel` or `Business travel`).
* **Class:** Travel class (`Eco`, `Eco Plus`, `Business`).

### ⏱️ Operational Metrics (Bottlenecks)
* **Flight Distance:** Distance of the journey in miles.
* **Departure Delay in Minutes:** Minutes the flight was delayed at departure. *(Critical for wait-time analysis)*.
* **Arrival Delay in Minutes:** Minutes the flight was delayed at arrival.

### ⭐ CX Touchpoints (Scored 0-5)
* **Ease of Online booking:** Rating of the booking process.
* **Online support:** Rating of digital customer service.
* **Departure/Arrival time convenient:** Rating of schedule convenience.
* **Checkin service:** Rating of the physical or digital check-in.
* **Gate location:** Rating of the boarding gate convenience.
* **On-board service:** Rating of the general service provided by staff.
* **Seat comfort:** Rating of the physical seating.
* **Leg room service:** Rating of space and comfort.
* **Food and drink:** Rating of catering services.
* **Inflight wifi service:** Rating of connectivity.
* **Inflight entertainment:** Rating of media options.
* **Cleanliness:** Rating of the environment's hygiene.
* **Baggage handling:** Rating of luggage delivery and care.

# 📖 Data Dictionary: Airline CX Operations

| Variable | Type | Category | Business Impact |
| :--- | :--- | :--- | :--- |
| **satisfaction** | Categorical | Target | Core KPI for brand health. |
| **Customer Type** | Categorical | Demographics | Used for segmentation and loyalty analysis. |
| **Age / Class** | Numeric/Cat | Demographics | Correlating demographic profiles with service expectations. |
| **Departure Delay** | Numeric | Operational | Leading indicator of friction and dissatisfaction. |
| **Arrival Delay** | Numeric | Operational | Measures service delivery failure. |
| **Service Ratings** | Ordinal (0-5)| CX Touchpoints | Granular data to identify specific process gaps (e.g., Wifi, Seat comfort). |
