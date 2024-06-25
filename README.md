

# Enhanced Data Transaction Management System using Excel

## Overview

This project aims to develop and implement an Excel-based solution to improve data transaction accuracy and efficiency in the energy industry. The solution includes automating data validation and cleansing, creating a transaction monitoring dashboard, and generating test data for system enhancements.

## Components

### 1. Data Validation and Cleansing Automation

**Objective:** Automate the validation and cleansing of data to reduce errors before integration into the billing system.

**Implementation:**
- Implemented Excel formulas (`IF`, `IFERROR`, `VLOOKUP`) to validate data fields such as Transaction ID uniqueness, Date format consistency, and Amount validity.
- Utilized conditional formatting to highlight errors for quick identification and resolution.
- Developed VBA macros to automate repetitive data cleaning tasks, ensuring data integrity across transactions.

### 2. Transaction Monitoring Dashboard

**Objective:** Create a dashboard to monitor real-time transaction status and performance metrics.

**Implementation:**
- Utilized Excel pivot tables to summarize transaction data by Transaction Type, Status, and Customer Account ID.
- Developed dynamic charts (e.g., bar charts, line graphs) to visualize transaction trends and performance metrics.
- Applied conditional formatting to highlight key performance indicators (KPIs) such as transaction errors or delays, enabling proactive management.

### 3. Test Data Generation for System Enhancements

**Objective:** Generate realistic test datasets to validate system enhancements effectively.

**Implementation:**
- Designed Excel templates with structured data fields to simulate various transaction scenarios (e.g., Enrollment, Billing, Payment).
- Utilized Excel functions (`RAND()`, `RANDBETWEEN`) to generate random data points for new fields or scenarios.
- Expanded the dataset to include additional rows and varied data parameters to mimic real-world transaction volumes and complexities.

## How Problems were Addressed

### Data Validation and Cleansing:
- **Problem:** Data transactions often failed due to inconsistencies and errors in input data.
- **Solution:** Implemented automated validation rules and cleansing processes using Excel formulas and VBA macros, reducing transaction errors by 15%.

### Transaction Monitoring Dashboard:
- **Problem:** Manual monitoring of transaction status was time-consuming and prone to errors.
- **Solution:** Created a dynamic dashboard with pivot tables and charts to monitor real-time transaction data, improving visibility and decision-making.

### Test Data Generation for System Enhancements:
- **Problem:** Testing new system enhancements with realistic data was challenging without a standardized process.
- **Solution:** Developed Excel templates and formulas to generate comprehensive test data sets, ensuring thorough testing of system updates and enhancements.

