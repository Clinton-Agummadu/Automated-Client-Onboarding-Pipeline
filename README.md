# 🤝 Automated Client Onboarding & Contract Pipeline

An autonomous client kickoff engine built in n8n that captures new client form submissions, leverages Groq LLMs to process project specifics, logs workspace records in Google Sheets, and triggers instant team alerts and client welcome emails.

---

## 🏗️ Workflow Architecture

1. **Webhook Ingestion:** Listens for incoming onboarding data payloads.
2. **Data Transformation:** Custom JavaScript cleanses and structures the payload.
3. **AI Scope Generation:** Groq LLM processes contract notes and generates personalized client communications[cite: 8].
4. **CRM Record Creation:** Logs the client profile and contract details in Google Sheets[cite: 8].
5. **Team Dispatch:** Fires a real-time Telegram notification to internal stakeholders[cite: 8].
6. **Client Outreach:** Automatically sends a formatted welcome email via Gmail[cite: 8].

---

## 🛠️ Tech Stack & Integrations

* **Automation Engine:** n8n[cite: 8]
* **AI/LLM:** Groq Chat Model (Basic LLM Chain)[cite: 8]
* **Database/CRM:** Google Sheets API[cite: 8]
* **Communication & Alerts:** Gmail API, Telegram Bot API[cite: 8]
* **Data Processing:** Custom JavaScript[cite: 8]

---

## 🚀 How to Setup

1. Download the `workflow.json` from this repository[cite: 8].
2. Import it into your **n8n** canvas[cite: 8].
3. Configure your API credentials for **Groq**, **Google Sheets**, **Telegram Bot**, and **Gmail**[cite: 8].
4. Set up your webhook URL on your client portal form and publish[cite: 8]!
