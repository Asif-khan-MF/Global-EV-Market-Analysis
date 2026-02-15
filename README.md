# Global Electric Vehicle Market Analysis (2015-2025)

![Dashboard Preview](images/Excel dashboard-Project 1.png)
*(The chart above visualizes the market trajectory, highlighting the recovery post-2023)*

## 1. Executive Summary
**The Situation:** Between 2015 and 2022, the EV market saw explosive growth. However, in 2023, sales dropped to 2.6M units, sparking fears of a permanent "EV Market Cooling."
**The Problem:** Investors and manufacturers needed to know: Was the 2023 dip a temporary correction or a sign of a bursting bubble?
**The Solution:** I analyzed a dataset of 3,022 EV models to forecast trends through 2028 and evaluate technical "gaps" like range vs. charging time.
**The Outcome:** The data confirms the market is resilient. Sales rebounded to 2.9M in 2025, with a forecast to breach **3.0 Million units by 2026**.

## 2. Tools & Skills Used
This project was executed entirely in **Microsoft Excel** to demonstrate advanced data manipulation and statistical forecasting capabilities.

* **Data Cleaning:** Standardized 3,000+ rows of raw data (handling missing values in Battery Capacity and Charge Time).
* **Pivot Tables:** Aggregated sales performance by Manufacturer (Tesla, BMW, BYD) and Region.
* **Analysis Toolpak:** Used for descriptive statistics to analyze the distribution of Battery Range (km) and Price.
* **Excel Forecasting:** Applied Exponential Smoothing (AAA) to generate lower and upper confidence bounds for 2026-2028 sales.
* **PowerPoint:** Synthesized findings into an executive presentation.

## 3. Data Structure
The analysis is based on `electric_vehicles_dataset.csv`, containing **3,022 records**. Key variables included:

| Variable | Description |
| :--- | :--- |
| `Units_Sold` | Primary KPI for market performance |
| `Battery_Capacity_kWh` | Used to analyze efficiency trends |
| `Range_km` | Key metric for consumer adoption analysis |
| `Charge_Time_hr` | Critical pain point identified in the analysis |
| `Price_USD` | Used to segment Luxury vs. Mass Market vehicles |

## 4. Key Insights & Analysis

### A. The "Dip" Was Temporary
Contrary to the "market collapse" theory, the 2023 dip (2.6M units) was a correction. The market immediately corrected upward in 2024 and 2025.
* **Evidence:** My forecast model predicts a steady growth trajectory, crossing 3M units in 2026 with a tight confidence interval.

### B. The "Range vs. Charging" Gap
A correlation analysis between `Range_km` and `Charge_Time_hr` revealed a technology gap.
* While average range has increased significantly (Mean: ~350km), charging times for mass-market models remain high (Avg: 6.2 hours).
* **Insight:** The barrier to adoption is no longer "Range Anxiety" but "Charging Patience."

### C. Manufacturer Performance
* **Volume Leaders:** Brands like Tesla and BYD continue to dominate volume.
* **Efficiency:** Analysis of `Price per km range` shows that while luxury models (Porsche, Lucid) offer high range, the cost-per-km remains prohibitive for mass adoption.

## 5. Recommendations
Based on the data, I recommend the following strategy for stakeholders:
1.  **Pivot to Charging Speed:** Manufacturers should prioritize lowering charge time over extending range beyond 500km, as range has hit a point of diminishing returns.
2.  **Focus on 2026 Inventory:** The forecast suggests a surge in demand for 2026; supply chains should prepare for >3M units volume.
3.  **Standardization:** The gap between fast-charging (30 mins) and standard charging (12 hours) must be bridged to capture the hesitant middle-market consumer.
