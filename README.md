# ⚖️ GenAI Legal Assistant for Indian SMEs

A **client-side AI-powered legal contract analysis tool** designed to help **Indian Small and Medium Enterprises (SMEs)** quickly understand contracts, identify risky clauses, and generate downloadable analysis reports — all **without uploading documents to any server**.

---

# Project Overview

Legal contracts are often lengthy and difficult to interpret, especially for non-legal professionals. This project provides an **AI-assisted contract analysis system** that works entirely in the browser to ensure **data privacy and security**.

The system supports **PDF, DOCX, and TXT** contract files and performs:
- Clause extraction  
- Risk identification  
- Summary generation  
- Downloadable PDF reports  

---

## 🎯 Key Features

- 📄 Upload contracts in **PDF / DOCX / TXT**
- 🔐 **100% client-side processing** (no backend, no data storage)
- ⚠️ Automatic **high-risk clause detection**
- 📊 Contract metrics dashboard
- 📝 Clause-wise risk table
- 📥 **Export analysis report as PDF**
- 🇮🇳 SME-focused legal keywords and risk indicators

---

## 🧠 How It Works

1. User uploads a legal contract file  
2. Text is extracted using:
   - **PDF.js** for PDFs
   - **Mammoth.js** for DOCX files
3. Contract is split into clauses
4. Rule-based NLP identifies **high-risk clauses** (e.g., indemnity, termination, penalty)
5. Risk metrics and summary are generated
6. User can download a **PDF analysis report**

---

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla JS)

### Libraries
- **PDF.js** – PDF text extraction
- **Mammoth.js** – DOCX text extraction
- **jsPDF** – PDF report generation

---

## 🧪 Risk Detection Logic

High-risk clauses are identified using keyword-based pattern matching such as:
- `indemnity`
- `termination`
- `penalty`
- `liability`
- `non-compete`

> ⚠️ This tool is intended for **assistance only**, not legal advice.

---

## 📊 Output Metrics

- Total number of clauses
- Number of high-risk clauses
- Overall contract risk level (Low / High)
- Clause-wise risk table
- Summary report

---

## 🔐 Privacy & Security

- No backend server
- No cloud storage
- Files never leave the user’s device
- Ideal for handling **confidential legal documents**

---

## 📂 Project Structure

