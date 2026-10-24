# Monthly Sales Reporting Automation

## Project Overview
This project documents an automated monthly sales reporting workflow using Microsoft Power Automate, SharePoint, and Power BI.

## Workflow Steps

1. **Receive the email** — Detect an incoming email containing a monthly sales CSV attachment.
2. **Validate the attachment** — Check that the received file meets the expected requirements.
3. **Store the CSV file** — Upload the validated file to the designated SharePoint folder used as the Power BI data source.
4. **Refresh Power BI** — Trigger a dataset refresh so the report uses the latest available sales data.
5. **Query the dataset** — Retrieve the required sales summary, including total quantity sold and the latest reporting period.
6. **Prepare the report** — Convert the query results into a CSV report.
7. **Send the report** — Email the generated report to the intended stakeholders.

## Technologies Used
- Microsoft Power Automate
- Microsoft SharePoint
- Microsoft Power BI
- CSV files
- Email automation

## Key Learning Outcomes
- Designing an end-to-end business automation workflow
- Automating file handling and validation
- Connecting data storage with business intelligence reporting
- Refreshing datasets and retrieving summary results
- Delivering automated reports by email

## Project Note
This repository documents the workflow design and implementation steps for learning and portfolio purposes. It does not contain the original business data, credentials, or private organizational resources.
