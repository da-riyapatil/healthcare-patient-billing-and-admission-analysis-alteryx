# Architecture Flow

## Workflow Overview
This project follows a simple Alteryx-based workflow for cleaning, checking, and summarizing healthcare patient data.

## Flow
Healthcare CSV Dataset  
→ Input Data in Alteryx  
→ Data Type Correction  
→ Branch 1: Column Summary for Data Review  
→ Branch 2: Negative Billing Filter  
→ Billing Amount Rounding  
→ Duplicate Removal  
→ Summarization for Visualization  
→ Pie Chart, Bar Chart, and Basic Table Outputs

## Step-by-Step Flow Description

### 1. Input Data
The workflow starts by loading the healthcare dataset from a CSV file into Alteryx.

### 2. Data Type Correction
Important fields are converted into proper formats so the data can be used correctly in the workflow.

Examples include:
- Age to integer
- Date of Admission to date
- Discharge Date to date
- Billing Amount to numeric
- Room Number to integer

### 3. Column Summary for Data Review
A separate branch is used to review column-level information and inspect the data for possible irregularities or outliers.

### 4. Negative Billing Filter
Records with negative billing amount values are removed so that only valid billing entries continue in the workflow.

### 5. Billing Amount Rounding
Billing values are rounded to improve readability and consistency in later outputs.

### 6. Duplicate Removal
Duplicate records are removed from the dataset to improve data reliability.

### 7. Summarization
The cleaned data is grouped and prepared for reporting and visualization.

### 8. Output Generation
The workflow produces:
- a pie chart for admission type distribution
- a bar chart for patient test result insights
- a basic table for summarized patient information

## Final Output
The final workflow converts raw healthcare records into cleaner and summarized outputs that support simple admission and patient-category analysis in Alteryx.