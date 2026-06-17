# 📊 PulseIQ — Workforce Health & Burnout Analytics Dashboard

**PulseIQ** is a Power BI dashboard built to monitor employee well-being, burnout risk, engagement, and attrition across an organization. It brings together HR metrics — stress, overtime, satisfaction, workload, and engagement — into a single set of interactive reports that help identify which departments and employee segments are most at risk, and why.

---

## 📌 Project Overview

Organizations often struggle to detect employee burnout and attrition risk before it becomes a retention problem. PulseIQ consolidates workforce data into four connected dashboard pages that track health metrics over time, break down risk by department, and surface the key drivers behind burnout and disengagement.

---

## 🎯 Objective

- Track organization-wide attrition rate, burnout, engagement, and stress levels.
- Identify which departments carry the highest attrition and burnout risk.
- Understand the relationship between burnout and employee engagement.
- Surface the key drivers contributing to burnout (workload, stress, overtime, satisfaction).
- Monitor trends over time (monthly, quarterly) to catch early warning signs.
- Provide a funnel view of how employees escalate from healthy to at-risk to attrition.

---

## 🗂️ Dashboard Pages

### 1. Workforce Health Overview
- KPI cards: Attrition Rate (19.18%), Avg Burnout (54.89), Avg Engagement (59.56), Avg Stress (54.79), Employee Count (1.47K)
- Burnout score by department (bar chart)
- Burnout score trend by month (line chart)
- Overtime hours by department and gender
- Engagement vs target gauge
- Department attrition risk heatmap (table)
- Employee distribution by burnout category (donut) and satisfaction category (pie)

### 2. Burnout Intelligence Analysis
- Burnout vs Engagement scatter plot
- Key drivers of burnout — waterfall chart (Workload, Stress, Overtime, Satisfaction → Total)
- Stress level trends by month and department
- Department-wise work-life balance trends over time (table)
- Drill-through detail visual for Burnout Score by Overtime Hours / Workload Score
- Employee distribution by department (pie)

### 3. Employee Risk Analysis
- Burnout trends by quarter, month, day, and department
- Employee satisfaction trends by month and department
- Stress category vs attrition outcome (stacked bar)
- High-risk employees by department
- Overtime hours vs burnout score trend (combo chart)
- **Employee Risk Escalation Funnel** — Total Employees → High Stress → High Overtime → High Burnout → Attrition Risk → Low Satisfaction

### 4. Forecasting and Insights
- Average burnout across departments by quarter (table with totals)
- Burnout vs Engagement by department (clustered bar)
- Burnout category distribution by department (100% stacked bar)
- Environment satisfaction distribution (donut)
- Overtime hours trend by month
- Multi-metric scatter: Overtime Hours, Burnout Score, and Stress Level by Employee/Department
- Attrition split (Yes/No) summary cards

---

## 📈 Key Metrics Tracked

| Metric | Description |
|---|---|
| Attrition Rate | % of employees who have left, overall and by department |
| Burnout Score | Composite score reflecting employee burnout level |
| Engagement Score | Measure of employee engagement vs. target (75) |
| Stress Level | Average stress score across departments/months |
| Overtime Hours | Total/average overtime worked, segmented by gender and department |
| Satisfaction Category | High / Moderate / Low employee satisfaction segments |
| Burnout Category | High Risk / Moderate Risk / Low Risk classification |
| Environment Satisfaction | Employee-rated satisfaction with work environment (1–4 scale) |

---

## 🏢 Departments Covered

- Human Resources
- Research & Development
- Sales

---

## 🔍 Key Insights

- **Human Resources** has the highest attrition risk (21.05%), followed by Research & Development (19.97%) and Sales (16.93%).
- Roughly **13% of employees fall into the High Risk burnout category**, with the majority (≈75%) in the Moderate Risk band.
- Burnout and engagement show a visible inverse relationship — higher burnout scores tend to cluster with lower engagement scores.
- **Workload and stress** are the largest positive contributors to burnout, while **satisfaction** acts as a mitigating factor in the waterfall breakdown.
- Overtime hours and burnout score trend upward together, suggesting overtime is a meaningful burnout driver.
- The risk escalation funnel shows a clear drop-off from "Total Employees" to "Attrition Risk," highlighting where intervention could have the most impact.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — data modeling, DAX measures, and dashboard visuals
- **Power Query** — data cleaning and transformation
- **DAX** — calculated KPIs (Attrition Rate, Avg Burnout, Engagement Target, etc.)

---

## 📁 Suggested Repository Structure

```
PulseIQ/
├── PulseIQ.pbix              # Power BI dashboard file
├── data/                     # Source/raw data (if shareable)
├── images/                   # Dashboard screenshots
├── docs/
│   └── Project_PulseIQ.pdf   # Exported dashboard report
└── README.md
```

---

## ⚙️ How to Use

1. Clone this repository.
2. Open `PulseIQ.pbix` in **Power BI Desktop**.
3. Refresh the data source if connected to a live dataset, or use the included sample data.
4. Navigate between the four report pages using the tabs at the bottom of the Power BI window.
5. Use slicers and cross-filtering (click on any chart segment) to drill into specific departments, months, or risk categories.

---

## 🚀 Future Enhancements

- Add predictive attrition modeling (e.g., using Power BI's built-in forecasting or an external ML model).
- Incorporate real-time data refresh via a connected HR system or data warehouse.
- Add manager-level drill-downs for team-specific burnout tracking.
- Build automated alerts for departments crossing burnout/attrition thresholds.
- Add a mobile-optimized layout for on-the-go HR review.

---

## ✅ Conclusion

PulseIQ turns scattered HR metrics into a unified, actionable view of workforce health. By connecting burnout, stress, overtime, engagement, and attrition data, it helps HR and leadership teams spot risk early, understand its root causes, and prioritize where to intervene.

---

## 👤 Author

*Add your name, role, and links (LinkedIn/GitHub) here.*
