# Promo and Apparel Business Unit Operations Dashboard

## Project Overview
The Promo and Apparel Business Unit report is a comprehensive tool designed to support the Vertical Manager in overseeing and managing the full lifecycle of jobs within the Promo and Apparel division. This report consolidates all relevant operational and performance data in one place, enabling efficient day-to-day management and strategic oversight.

## Strategic Value
This report empowers the Vertical Manager to manage with clarity, respond to issues before they escalate, and drive team accountability through real-time, actionable data. It supports our broader organizational goals of operational excellence, client satisfaction, and cross-team communication.

## Purpose and Use
The report equips the Vertical Manager with the insights needed to:
* Monitor job status across all stages from RFQ and estimating, to order entry, production, staging, and fulfillment.
* Track team performance, workload distribution, and process bottlenecks.
* Identify outstanding actions such as pending approvals, missing information, or production delays.
* Ensure alignment with delivery timelines, client expectations, and internal quality standards.

## Key Features
* **Full Job Lifecycle View:** Tracks every job through pre-production, production, and post-production.
* **Team-Level Accountability:** Highlights task owners, staging codes, and job readiness status.
* **Production Status Summary:** Provides quick visibility into jobs in WIP, on hold, completed, or delayed.
* **Sales and Order Metrics:** Integrates estimate/order values, RFQ conversion, and invoice status.
* **Data-Driven Management:** Enables real-time coaching, reallocation of resources, and proactive issue resolution.

## Tech Stack & Workflow
* **Data Extraction & Transformation:** **SQL** (Advanced Joins, CTEs, Window Functions) used to pull, transform, and unify raw data from CRM and ERP systems.
* **Data Cleaning & Preparation:** **Python** (Pandas, NumPy) utilized to clean data, handle missing values, and prepare the dataset for visualization.
* **Visualization & Analytics:** **Power BI** used to engineer the final interactive dashboards, calculating metrics like Daily Flash Reports, WIP tracking, and Quote Activity. 
* **Version Control:** **GitHub** utilized for script management and project documentation.

## Repository Structure
* `/data`: Contains the anonymized sample dataset (`sample_data.csv`) and the data dictionary. *(Note: All personal employee names, client names, and exact financial figures have been mocked or anonymized for data privacy).*
* `/scripts`: Includes the Python data cleaning scripts (`data_cleaning.py`) and SQL extraction queries (`data_extraction.sql`).
* `/dashboards`: Contains the packaged Power BI workbook (`operations_report.twbx`).
* `/images`: High-resolution screenshots of the dashboard views (Daily Flash, Estimate Trends, WIP Summary).

## Author
**Shubh Parekh**
* **GitHub:** [https://github.com/Shubh-3012](https://github.com/Shubh-3012)
* **Role:** Data Analyst / Business Analytics Specialist
