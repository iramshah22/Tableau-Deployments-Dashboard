# Tableau-Deployments-Dashboard

## Deployment Health & Performance Dashboard

A Tableau-based interactive dashboard designed to monitor and analyze deployment health across multiple environments. Built to provide real-time visibility into deployment success rates, failure patterns, and environment-wise distribution.

---

## 📊 Dashboard Overview

This dashboard provides a comprehensive view of deployment activities, helping teams identify bottlenecks, track trends, and improve release reliability.

### Key Metrics Tracked
| Metric | Value |
|--------|-------|
| **Total Deployments** | 540 |
| **Successful Deployments** | 305 |
| **Failed Deployments** | 235 |
| **Success Rate** | 56.5% |

---

## 📈 Visualizations Included

### 1. KPI Cards (Top Section)
- **Total Deployments** — Overall deployment count
- **Successful Deployments** — Green indicator for healthy releases
- **Failed Deployments** — Red alert for failures requiring attention

### 2. Detailed Deployment Records
Grouped bar chart showing **success vs. failure counts** across different targets:
- LM_Prod, MAI, RCT, RNT
- Quickly identifies which target has the highest failure rate

### 3. Monthly Deployment Trend Over Time
Line chart tracking deployment volume and health from **October 2025 to May 2026**:
- Green line = Successful deployments
- Red line = Failed deployments
- Identifies seasonal spikes and dips in deployment activity

### 4. Deployments by Environment (Donut Chart)
Distribution of deployments across environments:
- DevAll: 170
- EMT: 130
- SIT: 126
- UAT: 114

### 5. Breakdown of Failed Deployments by Error Type (Treemap)
Categorized failure analysis:
- Other Technical Errors: 96
- Duplicate Records: 64
- Missing Data/Fields: 27
- Permission Issues: 25
- Validation/Cross-Ref Errors: 23

---

## 🔍 Key Insights

- **March 2026** saw the highest deployment volume (171 deployments) with a significant spike in failures
- **DevAll** environment handles the most deployments, indicating it's the primary development/testing hub
- **"Other Technical Errors"** account for ~41% of all failures — suggests need for better error classification/logging
- **February 2026** had the lowest activity (6 deployments) — possible maintenance window or holiday period

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Tableau** | Dashboard design & visualization |
| **Python (Pandas, Faker)** | Dummy data generation |
| **CSV** | Data source for Tableau |

---

## ⚠️ Note on Data

&gt; **All data shown in this dashboard is dummy data**, generated solely for portfolio and demonstration purposes. No real production data or sensitive information is used.

---

## 🚀 How to Use

1. Download the `.twbx` packaged workbook
2. Open in Tableau
3. Interact with filters, hover for tooltips, and drill down by environment or time period


---

## 👤 Author

Built with ❤️ using Tableau for data visualization portfolio.
