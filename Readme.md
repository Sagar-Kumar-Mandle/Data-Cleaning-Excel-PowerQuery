# Data Cleaning Project - Power Query

## Table of Contents
- [Overview](#overview)
- [Sheet Details](#sheet-details)
- [Issues Identified](#issues-identified)
- [Goals for Data Cleaning](#goals-for-data-cleaning)
- [Tools I Used](#tools-i-used)
- [Conclusions](#conclusions)

---

## Overview
The Excel file contains raw data on stock purchases. The data is messy and not suitable for direct analysis. Data cleaning and preprocessing are required to make it analysis-ready and to derive meaningful insights.

---

## Sheet Details
| Sheet Name       | Description |
|------------------|-------------|
| **Raw Data**     | Unprocessed dataset directly extracted from the source database. Contains inconsistencies, missing values, and formatting issues. |
| **tbl_tabledata**| Cleaned, structured, and analysis-ready dataset suitable for reporting and visualizations. |

---

## Issues Identified 
- Client names contain stock exchange & stock ticker symbol.
- Poorly formatted contact names.
- Department & City data are merged in the same cell.
- Missing entries in the payment & revenue columns.
- Calculation Error in the Profit Margin Column.

---

## Goals for Data Cleaning
- Fill the missing cells with NA or 0.
- Display blanks for cells that contain calculation errors.
- Split client, contains stock exchange & stock ticker symbol into separate fields.
- Split Department & City into separate fields
- Remove extra space from the contact name and format it in a standardized manner.

---

## Tools I used
- **Microsoft Excel** - Structured Data Storage, Calculation & Formatting.
- **Power Query** - Automation, Data Cleaning & Data Transformation.

---

## Conclusions
The **tbl_tabledata** sheet contains cleaned datasets that can be used directly for reporting or further insights.

Datasets are suitable for presenting the data in a visualization form.