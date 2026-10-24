# Monthly Sales Reporting Workflow Diagram

```
flowchart TD
    A[Receive Monthly Sales Email] --> B[Identify CSV Attachment]
    B --> C[Validate CSV File]
    C --> D[Upload File to SharePoint]
    D --> E[Refresh Power BI Dataset]
    E --> F[Query Sales Summary]
    F --> G[Convert Results to CSV]
    G --> H[Email Report to Stakeholders]
```

## Workflow Summary

The process begins when a monthly sales email arrives. The attachment is validated and stored in SharePoint. Power BI is then refreshed, the required sales summary is queried, and the resulting CSV report is emailed to stakeholders.
