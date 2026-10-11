# 🏦 Financial Risk Analysis Dashboard (Power BI)

An interactive Power BI project that brings credit, market, and operational risk data into a single star-schema data model, so risk can be monitored by time, client, sector, and region.

## 📌 Project Overview

Financial institutions need to track several kinds of risk together. This project combines four data sources into one model to support risk monitoring and decision-making:

- **Credit risk:** loan portfolio data
- **Market risk:** market data
- **Operational risk:** operational loss data
- **Macroeconomic context:** economic indicators

Dimension tables for time, client, sector, and region let you slice every measure consistently across the report.

## 🧱 Data Model

The model contains 8 tables in a star-schema layout.

| Table | Type | Purpose |
|---|---|---|
| `loan_portfolio` | Fact | Loan-level data for credit risk analysis |
| `Market_Data` | Fact | Market data for market risk analysis |
| `Operational_Loss` | Fact | Operational loss events |
| `Economic_Indicators` | Fact | Macroeconomic indicators for context |
| `Dim_Time` | Dimension | Date and calendar attributes |
| `Dim_Client` | Dimension | Client attributes |
| `Dim_Sector` | Dimension | Industry sector |
| `Dim_Region` | Dimension | Geographic region |

## 📊 Key Metrics / KPIs

> Replace with the measures you built in Power BI.

- [e.g., Total Exposure]
- [e.g., Non-Performing Loan (NPL) Ratio]
- [e.g., Default Rate]
- [e.g., Total Operational Loss]
- [e.g., Risk by Sector / Region]

## 🛠️ Tools & Skills Used

- **Power BI Desktop**
- **Power Query** for data cleaning and transformation
- **Data Modeling** with a star schema and relationships
- **DAX** for calculated measures
- **Data Visualization** with interactive visuals, slicers, and drill-down

## 💡 Key Insights

> Add 3-5 findings from your dashboard, for example:

- [Which sector carries the highest risk exposure]
- [Which region has the highest default or loss rate]
- [How risk trended over time]
- [How economic indicators relate to portfolio performance]

## 🖼️ Dashboard Preview

> Add screenshots of your dashboard pages here.

```
![Dashboard Overview](images/dashboard_overview.png)
```

## 📁 Repository Structure

```
Financial-risk-analysis-dashboard-/
├── financial_risk_analysis.pbix   # Power BI report and data model
├── images/                        # Dashboard screenshots
└── README.md                      # Project documentation
```

## ▶️ How to Use

1. Download `financial_risk_analysis.pbix` from this repository.
2. Open it in **Power BI Desktop** (free to download from Microsoft).
3. Use the slicers and filters to explore risk by time, client, sector, and region.

## 🚀 Future Improvements

- Add forecasting for default and loss trends
- Add row-level security for role-based access
- Schedule automatic data refresh

## 👤 Author

**Kiran Thorat**
Data Analyst | Pune, India
📧 thoratk1107@gmail.com
💻 GitHub: [github.com/kirnthorat](https://github.com/kirnthorat)
🔗 LinkedIn: [add your profile link]
