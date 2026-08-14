# San Francisco Procurement Spend Analysis

## 1. Overview

This project analyzes public procurement data from the City and County of San Francisco to understand how procurement spending is distributed across departments, suppliers, procurement categories, and time.

The analysis combines Python-based data preparation and exploratory analysis with Power BI to convert raw procurement records into a management-oriented view of spending patterns and concentration.

## 2. Objectives

The project aims to:

* Analyze overall procurement spending and its distribution across departments and suppliers.
* Identify suppliers and procurement categories contributing most to total expenditure.
* Examine spending concentration and major procurement drivers.
* Analyze procurement spending trends over time.
* Identify patterns that could help management understand where procurement expenditure is concentrated.
* Present the analysis through an interactive Power BI dashboard.

## 3. Dataset

The project uses publicly available procurement data from the City and County of San Francisco.

Two datasets were used:

* **Procurement Contracts Data** — contains information related to procurement contracts, including contract-level and organizational information.
* **Procurement Payments Data** — contains payment-level procurement records used to analyze actual spending across suppliers, departments, procurement objects, and time.

The datasets represent different parts of the procurement process and were used together to provide a broader view of procurement activity.

Detailed dataset information is documented in [`DATA.md`](DATA.md).

## 4. Data Preparation & Methodology

The analysis was performed in Python using Pandas and NumPy.

The main preparation steps included:

* Loading and inspecting the raw procurement datasets.
* Reviewing column types and missing values.
* Cleaning relevant fields required for analysis.
* Standardizing fields used for grouping and aggregation.
* Converting relevant date and financial fields into appropriate formats.
* Identifying and handling data-quality issues.
* Creating analysis-ready datasets for procurement spend analysis.
* Aggregating spending by department, supplier, procurement object, and time period.
* Performing exploratory analysis to identify major spending patterns and concentration.

The cleaned data was then used to develop the Power BI dashboard.

## 5. Key Metrics

The analysis focuses on metrics that provide a high-level view of procurement activity:

* Total Procurement Spend
* Total Payments
* Supplier Spend
* Department Spend
* Procurement Object Spend
* Supplier Spend Concentration
* Spending Trends Over Time
* Top Suppliers by Spend
* Top Departments by Spend
* Top Procurement Objects by Spend

## 6. Dashboard Explanation

The Power BI dashboard is organized around three views.

### Page 1 — Procurement Spend Overview

Provides a high-level view of overall procurement spending.

It focuses on:

* Total procurement spend
* Spending trends
* Department-level spending
* Major procurement categories
* Overall distribution of expenditure

**Business question:**
Where is the organization's procurement spending concentrated?

### Page 2 — Supplier Spend Concentration

Focuses on supplier-level procurement spending.

It examines:

* Top suppliers by spend
* Supplier concentration
* Distribution of spending across suppliers
* Relative contribution of major suppliers

**Business question:**
Which suppliers account for the largest share of procurement spending?

### Page 3 — Procurement Spend Drivers

Examines the procurement categories and objects contributing most to expenditure.

It focuses on:

* Major procurement objects
* Spending by category
* Major spending drivers
* Department/category relationships

**Business question:**
Which procurement areas are driving overall expenditure?

## 7. Key Findings

The analysis identified several important patterns in San Francisco procurement spending:

* Procurement expenditure was concentrated among a relatively small group of suppliers.
* Certain departments accounted for a substantial share of overall procurement spending.
* Spending was unevenly distributed across procurement objects, with specific categories contributing disproportionately to total expenditure.
* Supplier-level analysis highlighted areas of significant spending concentration.
* Procurement spending patterns varied across departments and categories.

The exact quantified findings are presented in the analysis notebook and dashboard.

## 8. Limitations

The analysis has several limitations:

* The dataset represents recorded procurement activity and does not by itself explain whether a particular spending level was optimal or inefficient.
* High spending with a supplier or department does not necessarily indicate poor procurement performance.
* Supplier and department comparisons can be affected by differences in the type, scale, and nature of procurement requirements.
* The analysis is primarily descriptive and does not establish causal relationships between procurement decisions and spending outcomes.
* Public procurement data may contain missing values, inconsistent classifications, or changes in reporting practices over time.
* The analysis does not include all contextual factors that may influence procurement decisions.

## 9. Data Source

**Source:** City and County of San Francisco Open Data

The datasets used in this project are publicly available through the San Francisco open-data platform.

The original datasets were downloaded for analysis and processed using Python.

See [`DATA.md`](DATA.md) for information about the datasets used in the project.

## 10. Tools

* Python
* Pandas
* NumPy
* Power BI


```
