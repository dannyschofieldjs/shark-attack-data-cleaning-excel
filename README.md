# Shark Attack Data Cleaning and Analysis in Excel

## Project overview

This project demonstrates how I used Microsoft Excel to clean, standardise
and prepare a shark-incident dataset for analysis.

The original dataset contained approximately 690 records across 22 columns.
I reduced it to 11 analysis-relevant fields, addressed missing and duplicate
values, standardised categorical fields, and created a processed dataset
suitable for PivotTables and visual analysis.

## Business questions

The project was designed to support questions such as:

- How have reported incidents changed over time?
- Which countries and locations have the most recorded incidents?
- Which activities occur most frequently in the records?
- How do fatal and non-fatal incidents compare?

## Tools used

- Microsoft Excel
- Excel Tables
- Sort and Filter
- Conditional Formatting
- Excel formulas
- PivotTables
- PivotCharts
- Git and GitHub

## Repository structure

- `data/raw/` – original dataset
- `data/processed/` – cleaned Excel workbook
- `documentation/` – cleaning log and data dictionary
- `images/` – screenshots and exported charts

## Data-cleaning process

1. Preserved a copy of the source data.
2. Retained the 11 fields required for analysis.
3. Removed blank and duplicate records.
4. Checked and corrected duplicate case identifiers.
5. Derived missing years where possible.
6. Standardised missing categorical values as `unknown`.
7. Removed records without a country.
8. Standardised Age, Sex and Fatal fields.
9. checked the processed data using filters and charts.

## Key findings


- `[Country]` had the highest number of recorded incidents, with `[number]`.
- `[Activity]` was the most frequently recorded activity.
- `[percentage]%` of usable records were classified as fatal.
- Recorded incidents `[increased/decreased]` between `[year]` and `[year]`.

## Visualisations

![Incidents by year](images/attacks-by-year.png)

![Top countries](images/attacks-by-country.png)

![Top activities](images/attacks-by-activity.png)

## Limitations

- The dataset represents recorded reports and may not contain every incident.
- `unknown` represents missing or unusable source information.
- Some records are categorised as invalid or uncertain.
- Counts should not be interpreted as population-adjusted # Data source and attribution

The learning dataset was supplied as part of a Excel data-preparation
project and was derived from a publicly available shark-incident dataset.

Original dataset:
https://www.kaggle.com/datasets/mysarahmadbhat/shark-attacks

## Author

Daniel Schofield
