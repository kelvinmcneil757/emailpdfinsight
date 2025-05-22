# 📬 Email PDF Insight Workflow (AI-Powered Automation)

This project demonstrates how to automate the extraction of structured data and executive insights from emailed PDF reports using a GPT-4.1-powered AI agent and a modular no-code workflow.

## 🔧 How It Works

1. **Trigger**: Listens for new emails that contain a PDF attachment.
2. **File Extraction**: Parses the text from the attached PDF.
3. **AI Analysis**: Sends the extracted text to a GPT-4.1 AI agent with a structured prompt to:
   - Extract campaign-level metrics (e.g., budget, impressions, conversions)
   - Generate an executive summary
4. **JSON Transformation**: Parses and structures the AI's JSON response.
5. **Data Logging**: Appends the data into a Google Sheet or database for reporting.

## 🧠 Example Use Cases

- **Marketing Teams**: Log campaign results and summarize performance automatically.
- **Nonprofits**: Extract fields from emailed survey PDFs, log submissions, and generate automated summaries or scores.
- **Ops/Admin**: Automatically sort and organize any incoming form-based reports via email.

## ✨ Stretch Use Case

With minor changes to the AI prompt, this workflow can:
- Score each submission against defined criteria
- Categorize them (e.g., High Priority, Needs Follow-Up)
- Trigger downstream automation (Slack alerts, CRM updates, etc.)

## 🚫 API Keys Notice

This repo does not contain any credentials or API keys. You must configure your own OAuth and AI model credentials in your automation platform after importing the workflow file.

## 📁 Files

- `email_pdf_insight_workflow.json` — Importable workflow file (fully sanitized)

## 📬 Contact

Built during Weeks 4 & 5 of my AI automation journey.  
If you're interested in using this in your org, feel free to reach out or fork the workflow.

