# 311servicerequests
# 1. 01_data_ingestion.ipynb
- Loaded the raw CSV (`nyc_311_sample.csv`).
- converted to datetime (`Created Date`, `Closed Date`)
- Checked dupicated rows: 0 duplicates
- Checked null values (cleaned them in part 2)

# 2. 02_eda.ipynb
- Explored the service request status: most of them have been closed
- Further looked into missing values. dropped columns with > 90% missing values
- Identified the most common complaint types
- Analyzed trends by month, week, and hour of day
- Analyzed Requests by Borough, per capita by Borough (population was based on 2020 census)
- Created 4 charts: top complaints, seasonality by month, week, hour of the day

# KEY FINDINGS:

DATASET OVERVIEW:
  • Total Service Requests: 6,856,398
  • Time Period: 729 days (2023-08-25 to 2025-08-24)
  • Average Daily Requests: 9405

COMPLAINT INSIGHTS:
  • Most Common Complaint: Illegal Parking (15.3%)
  • Total Complaint Types: 220

TEMPORAL PATTERNS:
  • Busiest Month: Jan (month #1)
  • Busiest Day: Monday
  • Peak Hour: 10:00

 GEOGRAPHIC PATTERNS:
  • Busiest Borough: BROOKLYN (30.4%)
  • Total Boroughs: 6
