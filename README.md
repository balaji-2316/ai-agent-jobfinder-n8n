# 🚀 AI Agent Job Finder (n8n)

An AI-powered workflow automation built using **n8n** that collects job and internship opportunities from multiple sources, filters duplicates, evaluates them using **Google Gemini AI**, stores the best matches in **Google Sheets**, and sends real-time notifications via **Telegram**.

---

## 📌 Project Overview

Finding relevant AI and software jobs from multiple websites can be time-consuming. This workflow automates the entire process by:

- Fetching jobs from multiple job boards
- Combining and normalizing job data
- Removing duplicate listings
- Using Gemini AI to analyze and score each job
- Filtering high-quality opportunities
- Saving results to Google Sheets
- Sending Telegram notifications automatically

---

## ✨ Features

- 🔄 Automated daily execution
- 🌐 Collects jobs from multiple job portals
- 🤖 AI-powered job analysis using Gemini
- 📊 Job scoring and filtering
- ❌ Duplicate removal
- 📄 Stores results in Google Sheets
- 📲 Telegram notifications
- ⚡ Fully automated using n8n

---

## 🛠️ Tech Stack

- n8n
- Google Gemini API
- Google Sheets API
- Telegram Bot API
- HTTP Requests
- JSON
- Workflow Automation

---

## 📊 Workflow

1. Schedule Trigger
2. Fetch jobs from:
   - RemoteOK
   - Remote Jobs
   - Arbeitnow
   - Hugging Face Jobs
   - Y Combinator Jobs
3. Merge all job sources
4. Normalize job data
5. Filter valid jobs
6. Remove duplicates
7. Batch jobs
8. Analyze each job using Gemini AI
9. Parse AI response
10. Filter jobs based on AI score
11. Save results to Google Sheets
12. Send Telegram notification

---

## 📷 Screenshots

Add screenshots here:

- Workflow
- Google Sheets Output
- Telegram Notification

---

## 📂 Repository Structure

```
AI-Agent-JobFinder/
│
├── ai-job-finder-workflow.json
├── README.md
└── screenshots/
```

---

## ⚙️ Setup

1. Import the workflow JSON into n8n.
2. Configure:
   - Gemini API Key
   - Google Sheets Credentials
   - Telegram Bot Token
3. Activate the workflow.
4. Run it manually or wait for the scheduled trigger.

---

## 🎯 Future Improvements

- Resume matching using AI
- Web dashboard
- Email notifications
- Database integration
- User authentication
- Advanced job filtering

---

## 👨‍💻 Author

**Balaji V**

GitHub: https://github.com/balaji-2316

LinkedIn: *(Add your LinkedIn profile link here)*

---

## 📜 License

This project is available under the MIT License.
