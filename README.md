# 📄 Invoice Processor

An end-to-end **Invoice Processing System** built with:

- **Frontend:** React + Vite (for uploading PDF invoices)
- **Backend:** n8n (workflow automation for PDF parsing, LLM-based data extraction, Google Sheets logging, and email notifications)

---

## 🚀 Features
- Upload PDF invoices via the React frontend.
- Extracts key fields using an AI model:
  - Invoice Number
  - Client Name
  - Invoice Date
  - Due Date
  - PO Number
  - Subtotal, Tax, Total Amount
  - Notes & Terms
- Stores extracted data in Google Sheets.
- Sends formatted email notifications with invoice details.

---

## 🛠️ Setup Instructions

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/invoice-processor.git
cd invoice-processor
