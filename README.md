# AttachMate-n8n
Automated email attachment analysis using n8n and Python

-AttachMate is an automated email attachment analysis workflow built with n8n and Python. It receives emails, detects attached files, analyzes supported file types, and generates useful file insights automatically. The results are delivered through email and recorded in Google Sheets.

-Features
* Automated Email Monitoring & Attachment Detection
* Multi-Format File Processing
* Automated File Analysis & Insight Extraction
* Concise Report Generation
* Automated Email Report Delivery
* Google Sheets Integration for Result Tracking
* Fallback Handling for Unsupported Files

-How It Works
1. AttachMate receives an email and checks if it has a file attached.
2. If there is no attachment, it sends a response email.
3. If a file is attached, the workflow identifies whether it is CSV, XLSX, PDF, or another file type.
4. CSV and XLSX files are processed using Python, while PDF files are handled through a separate Python process.
5. The file information and key insights are prepared into a report.
6. The report is sent automatically by email and the results are saved in Google Sheets.
7. Unsupported files are handled through a fallback process.
