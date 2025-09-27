# Toronto-Crisis-Calls-Analytics
This project delivers a centralized Power BI dashboard for the Toronto Community Crisis Service (TCCS) and Crisis Call Team (CCT). It tracks call volume by dispatch type, case outcomes/status . The goal is to provide an at-a-glance operational view so leaders can optimize staffing, reduce time-to-response, and improve engagement outcomes.

# Toronto Community Crisis (TCCS) – Power BI Dashboard

A Power BI report that unifies 911 and community referral data to track **Crisis Call Team (CCT)** activity, outcomes, and response times for the City of Toronto.

## 📸 Snapshots

### Dashboard Overview
![TCCS Dashboard Overview](https://github.com/Mahidhar26/Toronto-Crisis-Calls-Analytics/blob/main/assets/tccs_overview.JPG))

### KPI Tiles
![TCCS KPI Tiles](https://github.com/Mahidhar26/Toronto-Crisis-Calls-Analytics/blob/main/assets/tccs_kpis.JPG))

---

## 🔎 What This Tracks

- **911 Requests by Dispatch Type** (e.g., Person in Crisis, Wellbeing Check, Distress, Thoughts of Self-Harm, Follow-Up)
- **CCT Status Outcomes** (Completed, Unable to Engage, Support Provided, Services Provided, Services Declined)
- **CCT Count by Dispatch Type**
- **Response Time Trend** (2023 → 2025)
- **Cases by Source & Timeline** (211, 2S Crisis Line, 911, EMS, TPS On Scene, Walk-In, etc.)  
  *Timeline coverage:* **Jan 2022 → Jan 2025**

---

## 🎯 KPIs & Goal Logic

| KPI                     | How It’s Calculated                                  | How Goal Is Set                                  |
|-------------------------|-------------------------------------------------------|--------------------------------------------------|
| Count of Sent to CCT    | Total cases logged as **“Sent to CCT”**               | Historical trend (previous months)               |
| Count of Dispatch Events| Total number of dispatch cases recorded               | Past dispatch patterns                           |
| Response Time           | (Arrival Time − Dispatch Time) / Total Cases          | Past performance or emergency service standards  |
| Transportation Requests | Total transport cases logged                          | Historical transport request demand              |

---

## 📈 Key Insights (from current build)

- **Demand mix:** *Person in Crisis* leads, followed by *Wellbeing Checks*; others are lower volume.
- **Outcomes:** **CCT Completed ≈ 13K** dominates; **Unable to Engage ≈ 4K**; **Support/Services Provided ≈ 2K each**; **Services Declined ≈ 1K**.
- **Response time:** Grew from 2023 → 2024, then **improved sharply** in early 2025.
- **Volume over time:** Ramped through 2024 with a late-year peak, easing into early 2025.

**Scorecard snapshot (period shown):**
- **Sent to CCT:** 19 (at goal)
- **Dispatch Events:** 3,682 (at goal)
- **Response Time:** 8.95 (≈ 53% better than goal 19)
- **Transportation Requests:** 4,950 (at goal)

---

## 🗂️ Repo Structure
├─ assets/
│ ├─ tccs_dashboard_overview.png
│ └─ tccs_kpi_tiles.png
├─ pbix/
│ └─ TCCS_Dashboard.pbix # (optional) Power BI file
├─ data/ # (optional) data extracts or sample CSVs
└─ README.md


## 📄 License

This project is released under the MIT License (see `LICENSE`).

## 👏 Acknowledgements

City of Toronto, partner helplines, and CCT staff for their continued service to community crisis response.
