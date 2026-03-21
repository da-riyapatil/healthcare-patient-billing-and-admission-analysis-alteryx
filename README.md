# Healthcare Patient Billing & Admission Analysis
![Alteryx workflow](<screenshots/Alteryx workflow.png>)

## Summary
This project is a beginner-friendly healthcare analytics project built in **Alteryx**. It focuses on cleaning patient-level healthcare data, validating billing values, preparing summarized outputs, and generating simple visual insights from the workflow.

## Business Problem
Healthcare datasets often contain raw patient records that need cleaning before analysis.

This project was built to answer simple questions such as:
- How are patients distributed across admission types?
- How are patients distributed across test result categories?
- How can billing data be cleaned and prepared for analysis?
- What basic patterns can be identified from healthcare records?

## Tools & Technologies
- Alteryx
- CSV dataset
- Basic workflow output charts and table

## Workflow
Healthcare CSV data  
→ Data type correction  
→ Negative billing amount filtering  
→ Billing amount rounding  
→ Duplicate removal  
→ Column summary and data review  
→ Summarization for reporting  
→ Pie chart, bar chart, and basic table outputs

## Key Insights
- Admission types are distributed quite evenly across the dataset
- Test result categories are also fairly balanced
- The workflow improves data quality by filtering invalid billing values and removing duplicates
- The project mainly demonstrates workflow-based data preparation and descriptive analysis in Alteryx

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
- Review the supporting documents inside the docs/ folder
- Check workflow and chart screenshots inside the screenshots/ folder
- Use the data dictionary in the data/ folder to understand the dataset fields