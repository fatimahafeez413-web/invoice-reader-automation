 Invoice & Receipt Reader Automation

An automation that reads invoices and receipts using AI, extracts key data, and logs it into a spreadsheet — no manual data entry needed.

 Demo Video
[Watch the walkthrough](https://www.loom.com/share/52215e39473f451e9a93347f0cde79bd)

 How It Works
1. A new invoice/receipt is dropped into a Google Drive folder
2. n8n automatically detects the new file
3. The file is downloaded and converted to base64
4. It's sent to Google's Gemini AI, which reads the document and extracts: vendor name, date, invoice number, line items, subtotal, tax, and total
5. The extracted data is automatically logged into a Google Sheet

Tools Used
n8n — workflow automation
Google Gemini API — AI-powered document reading
Google Drive— file storage/trigger
Google Sheets — data logging

Status
Fully working end-to-end: file upload → AI extraction → spreadsheet logging.

## Why I Built This
Manual invoice entry is repetitive and error-prone. This project automates the entire process, saving time and reducing mistakes — built as part of my transition into AI automation and freelancing.
