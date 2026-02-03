# 🧠 Stroke Healthcare Analytics: Clinical Outcomes & Mortality Dashboard

A high-fidelity clinical reporting tool built to evaluate stroke service demand and patient outcomes—utilizing Age-Standardized Mortality Rates (EASR), survival metrics, and regional benchmarking.

## 📝 Short Description / Purpose
The **Stroke Healthcare Analytics Dashboard** is a two-page, data-driven solution designed for Public Health Boards and Clinical Leads. By integrating hospital activity with mortality data, this tool moves beyond raw death counts to provide a statistically valid "apples-to-apples" comparison of regional performance. It identifies critical public health trends, such as premature mortality and survival ratios, to drive data-led clinical interventions.

## 🛠️ Tech Stack
The dashboard was built using a specialized healthcare data architecture:

📊 **Power BI Desktop** – Primary platform for advanced reporting and page navigation.

📂 **Power Query** – Used for complex data shaping and harmonizing disparate activity and mortality datasets.

🧠 **Advanced DAX** – Engineered for European Age-Standardized Rates (EASR), Mortality Ratios, and Year-over-Year (YoY) trend analysis.

📝 **Star Schema Modeling** – Architected a robust model utilizing Bridge Tables to synchronize Financial and Calendar year reporting across multiple fact tables.

🔬 **Statistical Normalization** – Applied age-standardization techniques to neutralize demographic biases in regional comparisons.

## 📈 Dashboard Features & Visuals

![Stroke Healthcare Analytics: Clinical Outcomes & Mortality Dashboard](https://github.com/vraj2602/Stroke-Activity-And-Mortality-Analysis-/blob/main/Stroke_Service_Activity_Dashboard.png?raw=true)

### 1. Page 1: Service Activity & Demand Patterns
**Operational KPIs:** Real-time monitoring of Total Discharges and Emergency vs. Scheduled Admission splits.

**Diagnosis Segmentation:** Slicers for Stroke, TIA, and Subarachnoid Haemorrhage to allow for granular pathway analysis.

**Demand Trends:** Longitudinal line charts mapping hospital pressure over a multi-year period.




### 2. Page 2: Mortality & Outcome Trends
![Stroke Healthcare Analytics: Clinical Outcomes & Mortality Dashboard](https://github.com/vraj2602/Stroke-Activity-And-Mortality-Analysis-/blob/main/Stroke_Mortality_Dashboard.png?raw=true)

**Outcome KPIs:** Highlights a 90.30% National Survival Rate and a Mortality Ratio of 97.05 per 1,000 discharges.

**Regional Benchmarking:** Uses a Stacked Bar Chart to compare Health Boards using Age-Standardized Rates (EASR), ensuring fair performance audits regardless of population age.

**Premature Mortality Analysis:** Pinpoints that 23.82% of fatalities occur under age 75, highlighting a critical area for early-intervention public health policy.

💡 **Clinical Impact & Insights**
* **Statistical Fairness:** By implementing EASR, the dashboard allows clinical leads to identify performance outliers that were previously hidden by "noisy" raw mortality data.

* **Risk Identification:** The discovery that nearly 1 in 4 stroke deaths are premature (<75) provides the evidence base for expanding screening programs in middle-aged demographics.

* **Outcome Optimization:** Integrating the Survival Rate % provides a positive performance metric, allowing hospitals to celebrate success and benchmark "best-in-class" recovery protocols.

* **Standardized Reporting:** Replaces fragmented spreadsheets with a single, interactive source of truth for national stroke audits.

## 📸 Screenshots / Demos
<img src="https://github.com/vraj2602/Stroke-Activity-And-Mortality-Analysis-/blob/main/Stroke_Service_Activity_Dashboard.png?raw=true" width="800">
<img src="https://github.com/vraj2602/Stroke-Activity-And-Mortality-Analysis-/blob/main/Stroke_Mortality_Dashboard.png?raw=true" width="800">

**Author:** Viraj Bhosale

**LinkedIn:** [Viraj Bhosale Profile](https://www.linkedin.com/in/viraj-bhosale-b9125a377?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
