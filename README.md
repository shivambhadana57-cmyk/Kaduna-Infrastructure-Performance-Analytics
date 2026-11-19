# Kaduna Infrastructure Performance Analytics

## Project Overview
This project evaluates Kaduna State infrastructure project data using Microsoft Power BI. It focuses on assessing the available project information, preparing the dataset, developing key performance indicators (KPIs), and presenting project portfolio insights through an interactive dashboard.

The project uses publicly available infrastructure and procurement information from the Kaduna State Public Procurement Authority (KADPPA).

## Objectives
- Inspect the quality and completeness of the infrastructure dataset.
- Clean and transform available fields using Power Query.
- Develop five DAX-based performance measures.
- Create an interactive Power BI dashboard with charts and slicers.
- Identify data limitations and provide recommendations for better project monitoring and reporting.

## Tools Used
- Microsoft Power BI Desktop
- Power Query
- DAX
- Microsoft Word
- GitHub

## Dashboard Contents
The Power BI report contains:
- 5 KPI cards
- 4 charts showing project status, project type, recorded budget by project type, and procuring entity
- 2 interactive slicers for project status and project type
- 2 report pages, with slicers synchronized across the pages

## Repository Structure
```text
Kaduna-Infrastructure-Performance-Analytics/
├── data/
│   ├── raw/
│   ├── processed/
│   └── README.md
├── power_bi/
│   ├── Kaduna_Infrastructure_Performance.pbix
│   └── README.md
├── screenshots/
│   ├── data_inspection/
│   ├── data_cleaning/
│   ├── dashboard/
│   └── evaluation/
├── report/
│   └── Kaduna_Infrastructure_Task3_Performance_Report.docx
├── documentation/
│   ├── dataset_source.txt
│   ├── kpi_definitions.md
│   └── evaluation_methodology.md
└── README.md
```

## Key Data Preparation Work
The original dataset was inspected using Power Query profiling features. Two completely empty columns were removed from the cleaned query. Text fields were trimmed and cleaned, date fields were checked, and missing values were assessed. The original query was preserved separately.

## Important Data Limitations
Several fields contain substantial missing information, including project start dates, end dates, tender details and bidder information. The sector and tender value fields were completely empty in the inspected dataset. These limitations affect the depth of project schedule and procurement analysis.

## Data Source
Kaduna State Public Procurement Authority (KADPPA):  
https://ipdata.kdsg.gov.ng/public/open-data

KADPPA Open Data Dashboard:  
https://ipdata.kdsg.gov.ng/

API Documentation:  
https://www.ocds.kdsg.gov.ng/api

## Project Deliverables
The repository contains the Power BI report, project documentation, screenshots and the separate Task 3 Word report.

**Note:** The dashboard is an analytical view of the available dataset. Missing dates and procurement fields mean that it should not be treated as a complete assessment of actual project delays or final expenditure.
