# Customer Growth, Retention & CLV — Analytics Case Study

This repository contains an end-to-end analytics case study analyzing customer
growth, retention behavior, lifetime value (CLV), revenue sustainability, and churn
risk using an anonymized e-commerce orders dataset.

The analysis demonstrates how analytics engineering techniques can be used to
translate raw transactional data into actionable insights for acquisition strategy,
revenue health assessment, and customer success prioritization.

---

## 📖 Analysis Overview

The notebook covers the following areas:

- **Cohort Retention & Resurrection Analysis**
  - Monthly cohort retention
  - Quality retention excluding low-value customers
  - Resurrection behavior after inactivity

- **Customer Lifetime Value & Acquisition Efficiency**
  - Behavior-based customer segmentation
  - Segment-level CLV estimation
  - CAC threshold recommendations using a 3:1 LTV:CAC framework

- **Growth Decomposition & Revenue Health**
  - Monthly revenue growth decomposition
  - New vs existing customer revenue
  - Net Revenue Retention (NRR)
  - Growth sustainability assessment

- **Customer Risk Scoring & Churn Prevention**
  - Customer health and risk scoring
  - Empirical churn probability estimation
  - Value-at-risk identification
  - Prioritized retention intervention list

---

## 📁 Repo Structure

```bash
├── customer_growth_retention_clv.ipynb
├── orders.csv
└── README.md
```

---

## 🛠 Tools & Technologies

- **Python** (pandas, numpy, matplotlib)
- **SQL** via **DuckDB**
- Google Colab–compatible notebook

SQL is used for set-based transformations and data modeling, while Python is used
for analytical logic, time-based modeling, and interpretation.

---

## ⚙️ Running the Notebook

### Option 1: Run on Google Colab (recommended)
1.	Open Google Colab
2.	Upload customer_growth_retention_clv.ipynb
3.	Upload the dataset (orders.csv)
4.	Update the dataset path (csv_file_path) in the notebook

### Option 2: Run locally (coming soon)
