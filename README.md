# Enterprise CRM Lead Sanitizer and Quality Dashboard

## 🚀 Overview
An enterprise-grade Excel data processing and hygiene system designed to ingest, clean, standardize, and score raw CRM lead lists[cite: 5]. This workbook eliminates messy data entry by automating syntax checks, duplicate detection, E.164 telephone formatting, and executive quality reporting.

---

## 📑 Multi-Sheet Architectural Structure

1. **`Raw_Input` (Tab 1)**
   * **Role:** Lead Ingestion Warehouse.
   * **Features:** Captures unformatted raw lead details including full names, unstandardized emails, messy phone numbers, company names, addresses, and lead sources.

2. **`Cleaning_Engine` (Tab 2)**
   * **Role:** Automated ETL & Data Standardization Layer.
   * **Features:** Uses advanced Excel formulas to split names, validate email syntax (`VALID` vs `INVALID SYNTAX`), detect duplicates (`UNIQUE` vs `DUPLICATE`), convert phone numbers into strict E.164 international formats, and calculate individual Lead Health Scores.

3. **`Data_QualityDashboard` (Tab 3)**
   * **Role:** Executive Command Center & Segment Control.
   * **Features:** Displays live KPI summary scorecards (Total Leads, Valid Leads, Duplicates, and overall Data Health percentage) alongside segmented dynamic lead tables.

---

## ⚙️ Technical Highlights
* **Automated Data Hygiene:** Instantaneous email syntax validation and duplicate tracking.
* **Global Phone Standardization:** Automated E.164 phone formatting for seamless CRM integrations.
* **Executive Visibility:** Real-time KPI summary cards and conditional formatting built for data analysts and sales operations teams.
