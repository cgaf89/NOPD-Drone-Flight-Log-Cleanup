# Drone Flight Log Data Cleaning & Audit

## Project Overview
A data cleaning and quality audit project using public municipal drone flight logs from Data.gov. The goal was to take a raw, inconsistent CSV export and prepare it for reliable analysis.

## Tools Used
* **Data Source:** Data.gov (Public Drone Flight Logs)
* **Spreadsheet Cleaning:** Apple Numbers
* **Version Control & Hosting:** GitHub

## Files in This Repository
* `raw-drone-flight-logs.csv` — The original, unedited dataset downloaded from Data.gov.
* `cleaned-drone-flight-logs.csv` — The standardized, analysis-ready dataset.

## Data Cleaning & Audit Summary
* **Removed Duplicates:** Checked for and removed duplicate flight entries.
* **Standardized Dates & Times:** Formatted all flight timestamps consistently (`YYYY-MM-DD HH:MM`).
* **Fixed Missing Values:** Audited blank cells in duration, altitude, and mission type columns, labeling missing entries as `N/A`.
* **Cleaned Text & Formatting:** Trimmed extra spaces, standardized capitalization, and verified numeric columns (such as flight duration and altitude) contained no stray text.
