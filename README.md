# HR Attrition Analysis (Excel)
Excel HR attrition analysis: data cleaning, pivot analysis, and interactive dashboard
<img width="1540" height="856" alt="HR_attrition_dashboard" src="https://github.com/user-attachments/assets/94c4c4f0-7bec-40f7-87a6-4eb9c7cf6eab" />

## Overview
Analysis of employee attrition for a 1,000-person company, answering: which employees are leaving, and what drives attrition? Built entirely in Excel - data cleaning through interactive dashboard.

## Data
Synthetic HR dataset (1,012 rows) with intentionally messy data for cleaning practice: duplicate records, inconsistent text values, numbers stored as text, and missing values.

## Data Cleaning
Removed 12 duplicate records (COUNTIF verification → Remove Duplicates)
Converted text-stored income values ("$5,200") to numeric
Standardized categorical variants ("HR" → "Human Resources", "M" → "Male", etc.) via TRIM + Find & Replace
Filled missing EducationField values with "Unknown"; left numeric JobSatisfaction blanks empty to preserve averages

## Key Findings
Attrition is concentrated among new hires (0–1 years) and overtime employees — and the risks stack: first-year employees working overtime leave at 46.3%, quadruple the rate of tenured staff without overtime (11.1%).
Job satisfaction shows a cliff, not a slope: employees rating it 1 leave at 30.9%, while ratings 2–4 all hover around 20%.
Attrition is nearly uniform across departments (21.4%–23.7%), ruling out team-specific causes.
Recommendation: focus retention on the first year of employment, reduce overtime load, and identify actively dissatisfied employees before they exit.

## Dashboard
Interactive Excel dashboard: KPI cards, 4 pivot charts, Department and Gender slicers wired to all visuals.

## Tools
Excel — pivot tables & charts, slicers, COUNTIF/AVERAGEIF/IFS, custom number formats, conditional formatting
