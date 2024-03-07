# SQL: ESRD Concept Dashboard
Utilized SQL to track active ESRD patients in the year 2022 for their first calcium, first sodium, first albumin, and first blood urea nitrogen lab values drawn each month.

[Link to the Tableau Dashboard](https://public.tableau.com/app/profile/ryan.lee1243/viz/Hospital-ESRD2022Dashboard/ESRD2022Census)

## Objective
The project aims to track whenever a patient either did not get their lab work done for a given month or failed to meet a target value and what percentage of the cohort met the hospital's goals.

### Relevant Metrics:
- Kidney transplant dates (if applicable)
- Patient's first calcium lab value for each month
- Patient's first sodium lab value for each month
- Patient's first albumin lab value for each month
- Patient's first blood urea nitrogen lab value for each month
- Percentage of patients meeting target for each lab value
  - Calcium: 50%, 8.4 to 9.4
  - Sodium: 75%, >= 37
  - Albumin: 60%, >= 4
  - Blood Urea Nitrogen: 80%, 5 to 20
- Race
- Age
- Patient's full name and geographic information
- Death date

### Inclusion Criteria:
- Patients with ICD9 dx of: 585.6 (ESRD dxs)
- ESRD must have been an active condition for the patient at some point in 2022
- Patient must have been active; that is, must have had an encounter in 2022 or 2021
- Months where patient was alive

### Exclusion Criteria:
- Months where patient received kidney transplant (procedure code = 55.69)

## Content
**SQL Code**

## Data
