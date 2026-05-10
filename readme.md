# QuickPay FinTech Operations Case Study

## Student Name

Kanak Lalchandani

## Student ID

[Your Student ID Here]

## Public GitHub Repository Link

[Add your public repository link here]

## Project Overview

This project is a fintech operations case study for QuickPay. It covers data cleaning, SQL business analysis, Python-based reconciliation, JSON normalization, and dashboard preparation for business monitoring.

## Repository Structure

```text
<repo-root>/
├── README.md
├── 01_data/
│   ├── raw/
│   │   ├── transactions_raw.csv
│   │   ├── merchant_master.csv
│   │   ├── users.csv
│   │   ├── ledger.csv
│   │   ├── gateway.csv
│   │   ├── exchange_rates.csv
│   │   └── api_response_sample.json
│   └── processed/
│       ├── cleaned_transactions.csv
│       ├── merchant_risk_summary.csv
│       ├── missing_in_gateway.csv
│       ├── missing_in_ledger.csv
│       ├── amount_mismatches.csv
│       ├── status_mismatches.csv
│       ├── reconciliation_report.csv
│       ├── api_normalized.csv
│       ├── daily_summary.csv
│       ├── payment_method_breakdown.csv
│       ├── region_breakdown.csv
│       └── merchant_performance_summary.csv
├── 02_spreadsheet/
│   ├── spreadsheet_workbook.xlsx
│   └── spreadsheet_answers.md
├── 03_sql/
│   ├── analysis_queries.sql
│   └── sql_answers.md
├── 04_python/
│   ├── fintech_pipeline.ipynb
│   └── summary_metrics.json
└── 05_visualization/
    └── dashboard_link.txt
```

## Tasks Completed

### 1. Spreadsheet Cleaning and Business Logic

* Cleaned and standardized raw transaction data.
* Standardized merchant names, dates, status values, risk scores, and gateway regions.
* Converted transaction amounts into USD using exchange rates.
* Enriched transactions using merchant master data.
* Added high value and high risk flags.
* Generated cleaned output and merchant risk summary.

### 2. SQL Business Analysis

* Wrote SQL queries for transaction status analysis, GMV by merchant, daily trends, chargeback analysis, regional risk analysis, and user failure patterns.
* Documented query logic and summaries.

### 3. Python Reconciliation Workflow

* Loaded ledger and gateway data.
* Checked duplicates and missing values.
* Identified missing records, amount mismatches, and status mismatches.
* Built a reconciliation report.
* Generated summary metrics in JSON format.

### 4. JSON Normalization

* Read the nested API response sample.
* Flattened the JSON into tabular format.
* Cleaned column names and date/time fields.
* Exported the normalized dataset.

### 5. Dashboard Visualization

* Built a Looker Studio dashboard for business monitoring.
* Included KPI cards, trend chart, breakdown charts, detailed table, and filters.

## Tools Used

* Microsoft Excel / Google Sheets
* SQL
* Python
* Pandas
* Jupyter Notebook
* Looker Studio
* GitHub

## How to Run the Project

1. Place all raw files inside `01_data/raw/`.
2. Open `02_spreadsheet/spreadsheet_workbook.xlsx` to review the spreadsheet logic and outputs.
3. Review `03_sql/analysis_queries.sql` for all SQL business queries.
4. Open `04_python/fintech_pipeline.ipynb` and run the notebook cells to reproduce reconciliation and JSON normalization outputs.
5. Use the processed files from `01_data/processed/` as dashboard sources.
6. Open the Looker Studio dashboard using the link stored in `05_visualization/dashboard_link.txt`.

## Submission Rules Followed

* All work is placed in the main branch.
* Required folders and filenames are preserved.
* No files are renamed or moved outside the required structure.
* A single public GitHub repository is used for submission.
* All written summaries are included in the required markdown files.

## Notes

* The final evaluation depends on both the working files and the written summary files.
* All outputs should remain in the specified locations for proper review.
