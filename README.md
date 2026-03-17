# Fintech KPI Dashboard

An interactive, tabbed KPI dashboard for B2B fintech startups — built to give founders, finance leads, and investors real-time visibility into the metrics that matter most.

---

## Live Demo

> [View the live dashboard here](https://aryanture1000-prog.github.io/fintech-kpi-dashboard)

Click through all four tabs — Overview, Growth, Unit Economics, and Risk.

---

## What's Inside

Four fully interactive dashboard tabs:

### Overview
- Monthly Revenue vs Target
- Active Client Growth
- Revenue breakdown by stream (Transaction Fees / Subscriptions / FX Spread)
- Full KPI health summary table with RAG status

### Growth
- YoY and MoM revenue growth rate
- New client acquisition per month
- ARPU trend
- Cumulative ARR trajectory

### Unit Economics
- LTV : CAC ratio with benchmark line
- CAC trend vs LTV÷3 threshold
- Gross margin and net margin by month
- Payback period

### Risk
- Churn rate trend
- Net Revenue Retention
- Burn Multiple vs target
- Cash runway in months

---

## KPIs Tracked

| Metric | Category | Frequency |
|---|---|---|
| MRR & ARR | Growth | Monthly |
| CAC by channel | Unit Economics | Monthly |
| LTV : CAC Ratio | Unit Economics | Monthly |
| Gross Margin % | Profitability | Monthly |
| Net Burn Rate | Risk | Monthly |
| Cash Runway | Risk | Monthly |
| Burn Multiple | Risk | Monthly |
| Churn Rate | Risk | Monthly |
| Net Revenue Retention | Growth | Monthly |
| Transaction Success Rate | Operations | Daily |

---

## Tech Stack

- Python 3.10+ — data pipeline and KPI calculation
- Streamlit — dashboard framework (production version)
- Chart.js — interactive chart rendering (demo version)
- pandas — data manipulation and aggregation
- Stripe API / QuickBooks API — live data sources (configurable)

---

## How to Use

```bash
git clone https://github.com/aryanture1000-prog/fintech-kpi-dashboard.git
cd fintech-kpi-dashboard
pip install -r requirements.txt
streamlit run dashboard.py
```

Connect your data source in `config.py` and the dashboard auto-populates with your company's live metrics.

---

## Customization

The dashboard is built to be fully customizable:
- Add or remove KPI cards
- Change benchmark targets per metric
- Connect any data source — CSV, API, SQL database
- White-label with your company branding

---

## Services

This dashboard is part of my freelance financial data practice. I build custom KPI dashboards, financial reporting systems, and data automation tools for fintech startups globally.

**Available for freelance engagements.**
Connect on [LinkedIn](https://linkedin.com/in/aryan-kasture) or reach out via GitHub.

---

## Author

**Aryan Kasture**
Financial Data Automation & Python Specialist
Mumbai, India

> Helping fintech startups turn messy financial data into clear decisions.
