# Workflow Architecture

## End-to-End Flow

```text
Incoming Email
      |
      v
Receive Monthly Sales CSV
      |
      v
Validate Attachment
      |
      v
Upload CSV to SharePoint
      |
      v
Refresh Power BI Dataset
      |
      v
Query Sales Summary
      |
      v
Convert Results to CSV
      |
      v
Email Report to Stakeholders
```

## Component Responsibilities

| Component | Responsibility |
|---|---|
| Microsoft Power Automate | Orchestrates the workflow and connects the steps |
| Email | Receives the monthly sales attachment and sends the final report |
| CSV | Carries the sales data and report results |
| SharePoint | Stores the source file for reporting |
| Power BI | Refreshes the dataset and provides sales summary results |

## Expected Outcome

A repeatable monthly reporting process that reduces manual file handling and report distribution.
