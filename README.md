\# Enterprise Banking Operations Analytics Platform



\## Project Overview



This project is an end-to-end corporate-style banking operations analytics solution built using Microsoft Fabric and Power BI.



The project simulates an internal banking environment where operational data such as business groups, building admin details, PICG/data ownership, service requests, approval workflow, SLA status, and audit logs are processed and analyzed.



\## Business Problem



Banking management needs a centralized dashboard to monitor internal operations, pending approvals, SLA breaches, business group workload, building admin ownership, PICG/data details, and audit activity.



\## Solution



The solution uses Microsoft Fabric Lakehouse to store raw, cleaned, and reporting-ready data using medallion architecture.



Power BI is used to create interactive dashboards for business users and management.



\## Tech Stack



\- Microsoft Fabric Trial

\- Fabric Lakehouse

\- Fabric Data Pipeline

\- Fabric Notebook

\- PySpark

\- Delta Tables

\- Power BI Desktop

\- DAX

\- GitHub



\## Architecture



The project follows Bronze, Silver, and Gold architecture:



\- Bronze Layer: Raw source data

\- Silver Layer: Cleaned and standardized data

\- Gold Layer: Business-ready fact and dimension tables



\## Main Modules



\- Business Group Analytics

\- Building Admin Details

\- PICG / Data Ownership

\- Service Request Monitoring

\- Approval Workflow Monitoring

\- SLA Breach Analysis

\- Audit and Governance Tracking



\## Repository Structure



```text

enterprise-banking-ops-fabric-powerbi/

│

├── data/

│   └── raw/

│

├── notebooks/

│

├── sql/

│

├── powerbi/

│   └── screenshots/

│

├── docs/

│

└── fabric/

