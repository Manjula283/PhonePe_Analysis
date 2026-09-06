# PhonePe Transaction Analysis 📊

A Power BI data analytics project exploring user and transaction behavior on a simulated PhonePe-style digital payments platform — covering money transfers, recharges & bill payments, loans, and insurance.

![Status](https://img.shields.io/badge/status-complete-brightgreen)
![Tool](https://img.shields.io/badge/tool-Power%20BI-yellow)
![Data](https://img.shields.io/badge/records-300K%2B%20transactions-blue)

---

## 📁 Repository Structure

```
PhonePe-Transaction-Analysis/
├── PhonePe_Analysis.pbix     # Power BI report (open in Power BI Desktop)
├── data/
│   └── Phonepe_Dataset.xlsx  # Source dataset (Users + Transactions)
├── images/                   # Chart exports used in REPORT.md
├── REPORT.md                 # Written analysis & key findings
└── README.md
```

## 📌 About the Project

This project analyzes **300,000 transactions** across **107,658 users** on a digital payments platform, built entirely in **Power BI**. It covers the full analyst workflow: data modeling, DAX measures, and interactive dashboard design.

The raw dataset has two tables:

| Table | Rows | Columns |
|---|---|---|
| `All_Users` | 107,658 | User_ID, Name, Age, Join_Date |
| `All_Transactions` | 300,000 | Transaction_ID, Amount, User_ID, Service, Service Type, Payment_Status, Reason, Date |

**Service categories covered:** Money Transfer, Recharge & Bill Payments, Loans, Insurance.

## 🎯 Objectives

- Track total transaction volume and value across services and over time
- Measure transaction success/failure rates and identify failure patterns
- Compare service categories (Loans, Insurance, Money Transfer, Recharges) by usage and value
- Analyze user growth and demographics

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, dashboard/report design
- **Excel** — source dataset
- **Python (pandas, matplotlib)** — supplementary analysis used to generate the summary charts in [REPORT.md](REPORT.md)

## 📈 Key Findings

See **[REPORT.md](REPORT.md)** for the full write-up with charts. Highlights:

- Overall transaction success rate: **96%**
- Total transaction value analyzed: **₹3.47 Billion**
- Loans account for the largest share of transaction value despite being only ~17% of transaction volume
- Money Transfer is the highest-volume service (150K of 300K transactions) but comparatively lower average ticket size

## 🚀 How to View

1. **Power BI Report:** Download `PhonePe_Analysis.pbix` and open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free) to explore the interactive dashboard.
2. **Dataset:** `data/Phonepe_Dataset.xlsx` contains the raw data behind the report.
3. **Report:** Read `REPORT.md` directly on GitHub for a quick summary of findings without opening Power BI.

## 👤 Author

Feel free to connect or raise an issue if you have questions or suggestions about this project.

---

⭐ If you found this project useful, consider giving it a star!
