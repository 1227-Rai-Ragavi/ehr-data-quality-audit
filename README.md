# EHR Data Quality Audit

## Overview
A Python-based audit tool that analyses Electronic Health Record (EHR) 
datasets for common data quality issues — missing fields, duplicate 
records, inconsistent formatting, and ICD-10 coding errors.

Built from 3+ years of live medical scribing experience across 6 EHR 
platforms. I know exactly where data quality breaks down because I've 
seen it firsthand.

## Problem Statement
Poor data quality in EHR systems leads to:
- Incorrect billing and claim rejections
- Misdiagnosis risk from incomplete records
- Failed audit compliance
- Unreliable analytics and reporting

## What This Project Does
- Loads a synthetic patient EHR dataset
- Checks for missing values across critical fields
- Flags duplicate patient records
- Validates ICD-10 code formatting
- Calculates a data quality score per record
- Outputs a clean audit report as CSV

## Tools Used
- Python 3
- pandas
- Google Colab (no installation needed)

## Dataset
Synthetic EHR data generated for portfolio purposes.
No real patient data is used.

## Files
| File | Description |
|---|---|
| `ehr_audit.ipynb` | Main analysis notebook |
| `sample_ehr_data.csv` | Synthetic input dataset |
| `audit_report.csv` | Output — flagged records with quality scores |

## Key Findings (Sample)
- 18% of records had missing chief complaint fields
- 7% contained duplicate patient entries
- 12% had incorrectly formatted ICD-10 codes
- Average data quality score: 74/100

## Author
Ragavi Rai — Healthcare Data Analyst  
[LinkedIn](https://www.linkedin.com/in/rai-ragavi)
