# 💳 Credit Card Weekly Dashboard

A comprehensive **Power BI dashboard** project that provides real-time insights into credit card key performance metrics and trends, enabling stakeholders to monitor and analyse credit card operations effectively.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Tech Stack](#tech-stack)
- [Data Pipeline](#data-pipeline)
- [Project Insights — Week 53](#project-insights--week-53)
- [Dashboard Features](#dashboard-features)
- [KPIs Tracked](#kpis-tracked)
- [Revenue Breakdown](#revenue-breakdown)
- [Customer Demographics](#customer-demographics)
- [Week-over-Week Revenue Table](#week-over-week-revenue-table)
- [Folder Structure](#folder-structure)
- [Getting Started](#getting-started)
- [License](#license)

---

## 📌 Project Overview

This project builds an end-to-end **Credit Card Weekly Dashboard** using **PostgreSQL** as the data backend and **Microsoft Power BI Desktop** as the visualisation layer. Raw transaction and customer data are ingested via CSV, stored in a relational database, and surfaced through interactive Power BI reports refreshed on a weekly basis.

---

## 🎯 Project Objectives

- Develop a **comprehensive weekly dashboard** for credit card performance monitoring.
- Provide **real-time insights** into key metrics and trends.
- Enable stakeholders to **analyse operations** across card categories, customer segments, geographies, and time periods.
- Track **Week-over-Week (WoW)** and **Year-to-Date (YTD)** performance.

---

## 🛠️ Tech Stack

| Layer              | Technology                  |
|--------------------|-----------------------------|
| Source Data        | CSV Files                   |
| Database           | PostgreSQL                  |
| Visualisation      | Microsoft Power BI Desktop  |
| Report Format      | Power BI (.pbix)            |
| Documentation      | LaTeX / Markdown            |

---

## 🔄 Data Pipeline

```
CSV File  ──►  PostgreSQL (Tables)  ──►  Import to Power BI  ──►  Dashboard
```

### Steps

1. **Prepare CSV File** — Structure raw credit card transaction and customer data into CSV format.
2. **Create Tables in PostgreSQL** — Design and create relational tables with appropriate schema and constraints.
3. **Import CSV into PostgreSQL** — Bulk load the CSV data into the PostgreSQL tables.
4. **Import Data from PostgreSQL into Power BI** — Connect Power BI Desktop to the PostgreSQL database as a live data source.

---

## 📊 Project Insights — Week 53 (31st Dec)

### 📈 Week-over-Week (WoW) Change
| Metric  | Change     |
|---------|------------|
| Revenue | **+28.8%** |

### 📅 Year-to-Date (YTD) Overview

| Metric                    | Value      |
|---------------------------|------------|
| Overall Revenue           | **$57M**   |
| Total Interest Earned     | **$8M**    |
| Total Transaction Amount  | **$46M**   |
| Male Customer Revenue     | **$31M**   |
| Female Customer Revenue   | **$26M**   |
| Blue & Silver Card Share  | **93%** of transactions |
| Top States (TX, NY, CA)   | **68%** of revenue |
| Overall Activation Rate   | **57.5%**  |
| Overall Delinquency Rate  | **6.06%**  |

---

## 📺 Dashboard Features

### Credit Card Transactions Report
- Revenue by **Payment Method** (Swipe, Chip, Online)
- Revenue by **Expenditure Category** (Bills, Entertainment, Fuel, Grocery, Food, Travel)
- Revenue by **Card Category** (Blue, Silver, Gold, Platinum)
- Revenue by **Education Level**
- Revenue by **Job Profile**
- **Quarterly Revenue & Transaction Count** (Q1–Q4)
- Filters: Gender | Income Group | Card Category | Quarter | Week

### Credit Card Customer Report
- Revenue by **Income Group** (Low, Med, High)
- Revenue by **Age Group** (20–30, 30–40, 40–50, 50–60, 60+)
- Revenue by **Top 5 States** (TX, NY, CA, FL, NJ)
- Revenue by **Marital Status**
- **Revenue by Week** trend line
- Revenue by **Gender** (donut chart)
- Customer Summary: Avg Age | Avg Income | CSS Score | Total CAC

---

## 📐 KPIs Tracked

| KPI                        | Value     |
|----------------------------|-----------|
| Total Revenue              | $57M      |
| Total Interest             | $8M       |
| Total Transaction Amount   | $46M      |
| Total CAC                  | $991K     |
| Activation Rate            | 57.5%     |
| Delinquency Rate           | 6.06%     |
| Average Customer Age       | 46.27 yrs |
| Average Customer Income    | $57K      |
| Customer Satisfaction (CSS)| 3.19      |

---

## 💰 Revenue Breakdown

### By Card Category

| Card Category | Transaction Amount | Interest Earned  | Revenue          |
|---------------|--------------------|------------------|------------------|
| Blue          | $37,840,749        | $6,614,172.62    | $47,188,611.62   |
| Silver        | $4,647,596         | $821,922.98      | $5,659,108.98    |
| Gold          | $2,091,362         | $384,755.16      | $2,533,682.16    |
| Platinum      | $953,314           | $161,629.05      | $1,135,608.05    |
| **Total**     | **$45,533,021**    | **$7,982,479.81**| **$56,517,010.81**|

### By Job Profile

| Job Profile   | Interest Earned    | Revenue           |
|---------------|--------------------|-------------------|
| Businessman   | $2,584,604.01      | $17,697,472.01    |
| White-collar  | $1,464,690.92      | $10,283,123.92    |
| Self-employed | $1,141,510.40      | $8,542,826.40     |
| Govt          | $1,182,230.84      | $8,335,533.84     |
| Blue-collar   | $967,751.42        | $7,040,606.42     |
| Retirees      | $641,692.22        | $4,617,448.22     |

---

## 👥 Customer Demographics

### Gender Split
| Gender | Revenue  | Share   |
|--------|----------|---------|
| Male   | $30.93M  | 54.73%  |
| Female | $25.59M  | 45.27%  |

### Top 5 States
| State | Revenue (Approx.) |
|-------|-------------------|
| TX    | $13M              |
| NY    | $13M              |
| CA    | $13M              |
| FL    | $8M               |
| NJ    | $9M               |

---

## 📆 Week-over-Week Revenue Table

| Week | Previous Revenue | Current Revenue | WoW Change |
|------|-----------------|-----------------|------------|
| 53   | $933,134        | $1,201,601      | ✅ +28.77% |
| 52   | $1,070,439      | $933,134        | 🔻 -12.83% |
| 51   | $1,026,549      | $1,070,439      | ✅ +4.28%  |
| 50   | $980,152        | $1,026,549      | ✅ +4.73%  |
| 49   | $1,008,777      | $980,152        | 🔻 -2.84%  |
| 48   | $1,047,120      | $1,008,777      | 🔻 -3.66%  |
| 47   | $1,078,915      | $1,047,120      | 🔻 -2.95%  |
| 46   | $1,094,927      | $1,078,915      | 🔻 -1.46%  |
| 45   | $1,063,063      | $1,094,927      | ✅ +3.00%  |
| 44   | $934,631        | $1,063,063      | ✅ +13.74% |
| 43   | $1,080,205      | $934,631        | 🔻 -13.48% |
| 42   | $982,974        | $1,080,205      | ✅ +9.89%  |
| 41   | $994,114        | $982,974        | 🔻 -1.12%  |
| 40   | $994,184        | $994,114        | 🔻 -0.01%  |
| 39   | $1,117,638      | $994,184        | 🔻 -11.05% |
| 38   | $1,097,403      | $1,117,638      | ✅ +1.84%  |
| 37   | $1,078,573      | $1,097,403      | ✅ +1.75%  |

---

## 📁 Folder Structure

```
credit-card-dashboard/
│
├── data/
│   ├── credit_card_transactions.csv     # Raw transaction data
│   └── credit_card_customers.csv        # Raw customer data
│
├── sql/
│   ├── create_tables.sql                # PostgreSQL table definitions
│   └── import_data.sql                  # Data import scripts
│
├── powerbi/
│   └── credit_card_dashboard.pbix       # Power BI report file
│
├── docs/
│   ├── credit_card_dashboard_report.tex # LaTeX project report
│   └── README.md                        # This file
│
└── screenshots/
    ├── transactions_report.png
    └── customer_report.png
```

---

## 🚀 Getting Started

### Prerequisites
- [PostgreSQL](https://www.postgresql.org/download/) (v13+)
- [Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
- A LaTeX distribution (optional, for the report) — [TeX Live](https://tug.org/texlive/) or [Overleaf](https://www.overleaf.com)

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/credit-card-dashboard.git
   cd credit-card-dashboard
   ```

2. **Set up PostgreSQL**
   ```bash
   psql -U postgres -f sql/create_tables.sql
   psql -U postgres -f sql/import_data.sql
   ```

3. **Open Power BI**
   - Launch Power BI Desktop
   - Open `powerbi/credit_card_dashboard.pbix`
   - Update the PostgreSQL connection string to point to your local database
   - Click **Refresh** to load latest data

4. **Compile the LaTeX report** *(optional)*
   ```bash
   pdflatex docs/credit_card_dashboard_report.tex
   pdflatex docs/credit_card_dashboard_report.tex   # run twice for TOC
   ```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

> **Built with** PostgreSQL · Power BI · LaTeX  
> *For queries or contributions, feel free to open an issue or pull request.*
