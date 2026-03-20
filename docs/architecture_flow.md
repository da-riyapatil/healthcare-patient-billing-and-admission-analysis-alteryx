# Architecture Flow

## Workflow Overview
This project follows a simple Alteryx-based analysis flow for healthcare patient billing and admission data.

## Flow
Healthcare CSV Dataset  
→ Input Data in Alteryx  
→ Data Cleaning and Standardization  
→ Data Type Correction  
→ Billing Value Validation  
→ Duplicate Removal  
→ Summarization and Aggregation  
→ Chart Outputs and Visual Summaries

## Step-by-Step Flow Description

### 1. Input Data
The workflow starts by loading the healthcare dataset from a CSV file into Alteryx.

### 2. Data Cleaning
Basic cleaning steps are applied to improve data quality, such as trimming text fields and preparing columns for analysis.

### 3. Data Type Correction
Important fields are converted into proper formats, such as:
- Age to integer
- Date of Admission to date
- Discharge Date to date
- Billing Amount to numeric
- Room Number to integer

### 4. Billing Validation
Records are checked to ensure billing values are valid, and negative billing amounts are filtered out.

### 5. Duplicate Removal
Duplicate patient records are removed using key dataset fields to make the analysis more reliable.

### 6. Summarization
The cleaned data is grouped and summarized to analyze:
- billing amount by medical condition
- patients by admission type
- patients by test results

### 7. Output Generation
The final workflow produces summarized outputs and basic charts for visual analysis.

## Final Output
The workflow helps convert raw healthcare records into clean and summarized outputs that can be used to understand patient admission patterns, billing distribution, and test result categories.