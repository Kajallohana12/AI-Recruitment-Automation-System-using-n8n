# 🤖 AI-Based Recruitment Automation System using n8n

## 📌 Overview

The **AI-Based Recruitment Automation System** is an intelligent workflow built with **n8n** that automates the recruitment process using AI. It reduces manual HR effort by automatically screening resumes, extracting candidate information, shortlisting applicants, scheduling interviews, and sending notifications.

---

## 🚀 Features

- 📄 Resume Upload through Webhook
- 🤖 AI-Based Resume Screening
- 👤 Candidate Information Extraction
- ✅ Automatic Shortlisting or Rejection
- 💬 WhatsApp Notifications
- 📝 AI-Generated Interview Questions
- 📅 Google Calendar Interview Scheduling
- ⚡ End-to-End Workflow Automation

---

## 🛠️ Tech Stack

- n8n
- Google Gemini AI
- Google Calendar API
- WhatsApp Business Cloud API
- Webhooks
- JSON

---

## 🔄 Workflow

```
Candidate Application
        │
        ▼
     Webhook
        │
        ▼
Resume Text Extraction
        │
        ▼
Candidate Information Extraction
        │
        ▼
AI Resume Analysis
        │
        ▼
 Shortlisted / Rejected
        │
        ├──────────────┐
        ▼              ▼
 WhatsApp         Rejection
 Notification      Message
        │
        ▼
Generate Interview Questions
        │
        ▼
Google Calendar Scheduling
        │
        ▼
Interview Confirmation
```

---

## 📷 Workflow Screenshot

> Add a screenshot of your n8n workflow here.

Example:

```
screenshots/workflow.png
```

---

## 📂 Project Structure

```
AI-Recruitment-Automation-n8n/
│
├── workflow.json
├── README.md
├── Project_Report.pdf
└── screenshots/
    ├── workflow.png
    ├── ai-analysis.png
    ├── whatsapp.png
    └── calendar.png
```

---

## ⚙️ How to Use

1. Clone or download this repository.
2. Import the `workflow.json` file into n8n.
3. Configure your credentials:
   - Google Calendar API
   - Google Gemini API
   - WhatsApp Business API
4. Activate the workflow.
5. Submit a candidate application through the webhook.

---

## 📈 Future Enhancements

- Email Notifications
- HR Dashboard
- Candidate Dashboard
- Zoom / Google Meet Integration
- Multiple Interview Rounds
- AI Ranking of Candidates

---

## 👩‍💻 Author

**Kajal Lohana**

Bachelor of Science in Software Engineering

SZABIST University, Karachi

---

⭐ If you found this project interesting, feel free to star the repository!
