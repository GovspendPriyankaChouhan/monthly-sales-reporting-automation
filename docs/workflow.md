
# Workflow Implementation Guide

## Project: Monthly Sales Reporting Automation

### Workflow Overview

This project demonstrates how Microsoft Power Automate connects email processing, SharePoint storage, and Power BI reporting to streamline monthly sales reporting.

### Step 1: Receive Sales Email
- Monitor incoming emails for monthly sales reports.
- Identify the email containing the CSV attachment.

### Step 2: Process the CSV Attachment
- Retrieve the email and its attachment.
- Extract the CSV data for processing.

### Step 3: Store the CSV in SharePoint
- Upload the incoming CSV file to the designated SharePoint folder.
- Use the folder as the source for the Power BI report.

### Step 4: Refresh the Power BI Dataset
- Trigger a dataset refresh after updating the source file.
- Make the latest available source data accessible to the report.

### Step 5: Query Sales Results
- Run a query against the Power BI dataset.
- Retrieve the required sales summary, according to the report's data model.

### Step 6: Generate the Report File
- Format the query results as CSV.
- Prepare the output for distribution.

### Step 7: Email the Report
- Send the generated report to the intended stakeholders.
- Automate the final reporting and distribution step.

## Expected Benefits
- Reduces repetitive manual reporting tasks.
- Connects data processing and reporting stages.
- Improves consistency in report distribution.
- Makes the monthly reporting process easier to repeat.

## Implementation Requirements
The complete workflow requires appropriate access, permissions, and configured connections for Outlook, SharePoint, Power Automate, and Power BI.

This guide documents the intended workflow for learning and portfolio purposes. It does not claim that the end-to-end automation has been deployed or tested in the author's environment.
