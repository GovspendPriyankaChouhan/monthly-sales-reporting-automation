# Monthly Sales Reporting Automation

## Project Overview

This project documents an automated monthly sales reporting workflow using Microsoft Power Automate, SharePoint, and Power BI.

The objective is to reduce repetitive manual work involved in receiving sales data, updating the reporting source, refreshing the Power BI dataset, and distributing sales summaries.

## Business Problem

Monthly sales reporting often requires several manual activities, including processing email attachments, updating data sources, refreshing reports, and sharing results with stakeholders.

This workflow demonstrates how these activities can be connected into a structured automation process.

## Tools and Technologies

- **Microsoft Power Automate:** Workflow orchestration and automation.
- **Microsoft Outlook:** Receiving monthly sales emails and sending report emails.
- **SharePoint:** Storing CSV files used as the reporting data source.
- **Microsoft Power BI:** Refreshing the dataset and analyzing sales data.
- **CSV:** Data exchange format for incoming sales files and report output.

## Workflow Steps

1. **Receive the monthly sales email**  
   Detect an incoming email containing a sales CSV attachment.

2. **Process the CSV attachment**  
   Identify and process the incoming sales file.

3. **Store the source file in SharePoint**  
   Upload the CSV to the designated SharePoint folder used by the Power BI report.

4. **Refresh the Power BI dataset**  
   Trigger a dataset refresh so the report can use the updated source data.

5. **Query the sales results**  
   Run a Power BI dataset query to retrieve the required sales summary, including total sales where defined by the report's data model.

6. **Format the report output**  
   Convert the query results into a CSV report for distribution.

7. **Email the report to stakeholders**  
   Send the generated report to the intended recipients.

## Expected Outcome

The workflow is designed to streamline monthly sales reporting, reduce repetitive manual steps, and make updated sales summaries easier to distribute.

## Project Scope

This repository focuses on the workflow design, implementation steps, tools, and concepts learned through the project.

It does not contain the original sales datasets, credentials, or private organizational resources. Execution depends on access to the required Microsoft services and correctly configured connections.

## Key Learning Areas

- Workflow automation and trigger-based processes
- Email attachment processing
- CSV data handling
- SharePoint integration
- Power BI dataset refresh and querying
- Automated report distribution
- Connecting multiple Microsoft services in a business workflow

## Disclaimer

This repository is a project walkthrough for learning and portfolio purposes. The documented workflow represents the intended process; successful end-to-end execution requires the appropriate Microsoft environment, permissions, and service connections.
