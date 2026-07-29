# HR & Salary Analytics Dashboard

An end-to-end Power BI dashboard built to analyze workforce demographics, employee performance, and salary distribution across departments and seniority levels.

## Features

* **Workforce Demographics:** Overview of headcount, age distribution, education levels, and work modes.
* **Talent & Retention:** Employee grouping based on performance scores, satisfaction levels, and promotion metrics.
* **Compensation Analysis:** Historical salary trends (2014–2025), gender pay gap overview, and department-level pay breakdowns.
* **Interactive Tooltips:** Custom page tooltips filtered dynamically by seniority level and category.

## Technical Details

* **Data Modeling:** Star Schema connecting employee demographics with annual salary records.
* **Calculations:** DAX measures for headcount, average and median salaries, and dynamic filter handling.
* **Filtering:** Cross-filtering enabled between relational tables to support drill-downs and page-level tooltips.

## Repository Contents

* `newreport.pbix` — Complete Power BI report file.
* `departments (1).csv` — Department mapping data.
* `employees (1).csv` — Employee profile and demographic data.
* `locations.csv` — Geographic location details.
* `org_edges.csv` — Organizational hierarchy data.
* `promotions.csv` — Historical career mobility records.
* `salaries_annual.csv` — Annual compensation and salary data.
