# Invoice Processing Agent (Doc AI)

An AI workflow that reads invoices and turns them into clean, organized spreadsheet data, with no manual typing.

## The Problem
Typing invoice details into spreadsheets is slow and full of mistakes. Invoices also arrive in different formats and from different places.

## What It Does
- Accepts invoices from a form upload, email, Google Drive, or website upload
- Handles JPEG, PNG, WEBP, and PDF files
- Reads PDFs with Mistral AI OCR, even scanned ones
- Extracts invoice number, dates, vendor and customer details, tax, totals, and currency
- Captures every line item: description, quantity, unit price, and line total
- Saves header info and line items to separate tabs in Google Sheets
- Updates existing rows to prevent duplicates
- Stores the invoice in a Google Drive "invoices" folder
- Emails the file link to the person who submitted it

## How It Works
Invoice uploaded → File type check → OCR for PDFs → AI data extraction → Save to Google Sheets → File to Google Drive → Confirmation email
<img width="926" height="407" alt="Screenshot 2026-11-17 035024" src="https://github.com/user-attachments/assets/5e997370-487b-47d4-844d-0d9d4955f022" />


## Tech Stack
n8n, Mistral AI (OCR and AI agents), Google Sheets, Google Drive, Gmail

## Result
Faster bookkeeping, fewer typing mistakes, and a searchable record of every invoice.

## Want Something Like This?
I build custom AI automations for businesses.
Website: https://justmyaiagency.com
