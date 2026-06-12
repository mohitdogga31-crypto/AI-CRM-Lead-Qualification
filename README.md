# AI CRM Lead Qualification using n8n

An intelligent CRM automation workflow built using **n8n** and **Google Gemini AI** that automatically evaluates incoming leads, assigns lead scores, and routes them based on their quality.

## Overview

Manually reviewing every lead can be time-consuming and inconsistent. This workflow uses AI to analyze lead information and determine which prospects deserve immediate attention.

The system automatically scores leads, categorizes them, stores them appropriately, and notifies sales teams about high-value opportunities.

---

## Features

- Automated lead intake through n8n forms
- AI-powered lead qualification using Google Gemini
- Lead scoring from 0–100
- Classification of leads based on quality
- Conditional routing using IF logic
- Google Sheets integration for lead storage
- Telegram notifications for qualified leads
- Separate tracking for qualified and non-qualified prospects

---

## Workflow

### 1. Form Submission
Leads submit their information through an n8n form.

### 2. AI Analysis
Google Gemini analyzes the submitted data and returns:
- Lead Score
- Qualification Status
- Reasoning

### 3. Data Structuring
The workflow extracts the AI response into structured fields.

### 4. Decision Making
An IF node evaluates whether the lead meets the qualification criteria.

### 5. Qualified Leads
If the lead score exceeds the defined threshold:
- The lead is stored in Google Sheets.
- A Telegram notification is sent instantly.

### 6. Non-Qualified Leads
If the lead does not meet the threshold:
- The lead is stored in a separate Google Sheet for future follow-up campaigns.

---

## Technologies Used

- n8n
- Google Gemini AI
- Google Sheets
- Telegram Bot API

---

## Use Cases

- Sales teams prioritizing high-value leads
- Small businesses automating lead qualification
- Agencies managing large volumes of inquiries
- Startups improving response efficiency

---

## Benefits

- Reduces manual lead review
- Saves time for sales teams
- Ensures consistent qualification criteria
- Enables faster responses to promising prospects
- Maintains records of all incoming leads

---

## Workflow Screenshot
<img width="1919" height="907" alt="ai-crm lead workflow" src="https://github.com/user-attachments/assets/6009ea3e-1f40-416c-ab33-dbd7185037eb" />
## Execution screenshot
<img width="1915" height="903" alt="ai-crm lead execution" src="https://github.com/user-attachments/assets/2406ce39-a5c7-4601-b32d-e5271eaa598d" />
<img width="1919" height="916" alt="ai-crm lead execution 2" src="https://github.com/user-attachments/assets/58e110fc-ca81-4aec-a534-c13588f5be68" />

## Future Improvements

- CRM integrations (HubSpot, Salesforce)
- Email notifications
- Advanced lead scoring criteria
- Automated follow-up sequences
- Analytics dashboard

---

## Author

Built as part of my AI Automation portfolio using n8n.
