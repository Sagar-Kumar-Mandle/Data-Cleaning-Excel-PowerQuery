# Data Cleaning Project: Power Query + Excel Functions + Structured Tables


## Table Contents
- [Overview](#overview)
- [Sheet Details](#sheet-details)
- [Issues Identified](#issues-identified)
- [Goals for Data Cleaning](#goals-for-data-cleaning)
- [Tools I Used](#tools-i-used)
- [Conclusions](#conclusions)

---

## Overview
The Excel file contains live-shows concert & ticket sales details. The data is messy and not suitable for direct analysis. The datasets require significant cleaning and transformation before they are suitable for further analysis.

---

## Sheet Details
| Sheet Name       | Description |
|------------------|-------------|
| **Dirty Data**     | Unprocessed dataset is directly extracted from the source database.  |
| **Merge Data**| Data from different sources merges into a single table, including additional details. |
| **Clean Data** | Cleaned, structured, and analysis-ready dataset suitable for reporting and visualizations |

---

## Issues Identified 

- Multiple Datasets are not stored in a structured format
- Country entries are missing.
- Unnecessary spaces exist in the person's column.
- Some records are missing their currency code.
- Time and Date are mixed into a one-cell that contains unnecessary text.

---

## Goals for Data Cleaning
- Add the missing currency and country data to the main source datasets.
- Merge both datasets into a single table.
- Remove the currency symbol from the Ticket Price column.
- Retrieve Time & Date from Event Details column and store in different columns. If no data is available, then replace it with "TBA".

---

## Tools I used
- **Microsoft Excel** - Structured Data Storage, Calculation & Formatting.
- **Power Query** - Automation, Data Cleaning & Data Transformation.

---

## Conclusions
The **Clean Data** sheet contains cleaned datasets that can be used directly for reporting or further insights.

Datasets are suitable for presenting the data in a visualization form.