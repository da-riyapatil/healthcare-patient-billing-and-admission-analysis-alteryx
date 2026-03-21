# Data Dictionary

| Column Name | Description |
|---|---|
| Name | Patient name |
| Age | Age of the patient |
| Gender | Gender of the patient |
| Blood Type | Blood group of the patient |
| Medical Condition | Main medical condition linked to the patient record |
| Date of Admission | Date when the patient was admitted |
| Doctor | Doctor assigned to the patient |
| Hospital | Hospital name |
| Insurance Provider | Patient's insurance provider |
| Billing Amount | Billing amount linked to the patient record |
| Room Number | Room number assigned during admission |
| Admission Type | Type of admission such as Elective, Urgent, or Emergency |
| Discharge Date | Date when the patient was discharged |
| Medication | Medication linked to the patient record |
| Test Results | Test result category such as Normal, Abnormal, or Inconclusive |

## Notes
- This dataset is used for workflow-based cleaning and analysis in Alteryx
- Billing Amount was validated and cleaned during workflow processing
- Some fields were type-corrected before analysis
- The workflow also includes column summary review, duplicate removal, and summarized outputs for reporting