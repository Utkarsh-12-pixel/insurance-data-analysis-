# Prism Insurance Dashboard - Power BI

A Power BI dashboard I built to analyze insurance data for a fictional company called Prism Insurance Pvt. Ltd.

## What this project does

The dashboard gives a quick overview of the company's policy and claims data — things like how much premium was collected, how many claims were settled vs rejected, and which age groups are claiming the most.

There are two pages:
- **Page 1** – Main dashboard with charts and KPIs
- **Page 2** – Detailed data table with drill-through filter

## Dataset

The dataset (`InsuranceData.csv`) has around 10,000 rows with details like policy type, customer age, gender, premium amount, coverage, claim status, and claim amount.

Policy types covered: Auto, Health, Home, Life, Travel

## Tools used

- MS SQL Server (to store and query the data)
- Power BI Desktop (to build the report)
- Power BI Service (to publish and schedule refresh)

## Some things I implemented

- Slicers for filtering by policy, claim, and customer
- Drill-through filter on the data table page
- Scheduled data refresh on Power BI Service
- Row-Level Security (RLS) to restrict data by role

## How to use

1. Clone the repo
2. Import `InsuranceData.csv` into SQL Server
3. Open `prism_insurance.pbix` and update the data source connection
4. Hit refresh and you're good to go

