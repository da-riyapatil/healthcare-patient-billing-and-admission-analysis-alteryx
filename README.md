# Healthcare Patient Billing & Admission Analysis

## Summary
This project is a beginner-friendly healthcare analytics project built in **Alteryx**. It focuses on preparing patient-level healthcare data, analyzing billing and admission patterns, and generating simple visual summaries from workflow outputs.

## Business Problem
Healthcare data often contains multiple patient and billing fields that need cleaning and summarization before analysis.

This project was built to answer simple operational questions such as:
- How are patients distributed across admission types?
- How does billing amount vary by medical condition?
- How are patients distributed across test result categories?
- What basic patterns can be identified from healthcare admission and billing data?

## Tools & Technologies
- Alteryx
- CSV dataset
- Basic charts from workflow outputs

## Workflow
Healthcare CSV data  
→ Data cleaning and type correction in Alteryx  
→ Duplicate removal and billing validation  
→ Summarization by condition, admission type, and test result  
→ Output charts and visual summaries

## Key Insights
- Billing amount is distributed fairly evenly across major medical conditions
- Patient counts are almost evenly split across **Elective**, **Urgent**, and **Emergency** admission types
- **Normal**, **Abnormal**, and **Inconclusive** test result groups are also balanced in the dataset
- The project is useful for showing workflow-based healthcare data preparation and descriptive analysis in Alteryx

## Repository Structure
```text
healthcare-billing-admission-analysis/
│
├── workflows/
│   └── healthcare_analysis_workflow.yxmd
│
├── docs/
│   ├── project_summary.md
│   ├── architecture_flow.md
│   ├── insights_and_recommendations.md
│
├── data/
│   └── data_dictionary.md
│
├── screenshots/
│   └── (workflow + output charts)
│
├── README.md
└── .gitignore
```

## How to View Project

- Open the Alteryx workflow file from the workflows/ folder
- Review project documentation inside the docs/ folder
- Check workflow and chart screenshots inside the screenshots/ folder
- Use the data dictionary in the data/ folder to understand dataset fields