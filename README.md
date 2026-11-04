# 🚀 Startup Funding Summarizer

An AI-powered automation workflow built using **n8n** and **Google Gemini** to collect, analyze, and summarize startup funding news from RSS feeds.

## 📌 Project Overview

The Startup Funding Summarizer automatically collects startup funding-related news articles, combines the information, and uses Google Gemini to generate a summarized report. The report is then delivered through Gmail.

This project demonstrates how Generative AI and workflow automation can simplify information gathering and reporting.

## ✨ Key Features

- Automated execution using Schedule Trigger.
- Collects startup funding news through RSS feeds.
- Aggregates multiple news articles.
- Uses Google Gemini to generate AI-powered summaries.
- Sends the generated report through Gmail.
- Reduces manual news research and reading time.

## 🛠️ Technologies Used

- **Automation Platform:** n8n
- **AI Model:** Google Gemini
- **Data Source:** RSS Feed
- **Email Service:** Gmail
- **AI Technique:** Prompt Engineering and LLM-based Summarization

## ⚙️ Workflow Architecture

1. **Schedule Trigger:** Starts the workflow automatically.
2. **RSS Read:** Fetches startup funding news.
3. **Aggregate:** Combines collected articles.
4. **Basic LLM Chain:** Processes the information using Google Gemini.
5. **Gmail:** Sends the generated funding summary.

## 📂 Project Structure

```text
Startup-Funding-Summarizer/
│
├── README.md
└── Startup_Funding_Summarizer_GitHub_Safe.json
```

## 🚀 Setup Instructions

1. Install or access an n8n instance.
2. Download the workflow JSON file from this repository.
3. Open your n8n workspace.
4. Import the downloaded JSON workflow.
5. Configure your RSS feed URL.
6. Connect your Google Gemini credentials.
7. Configure your Gmail credentials and recipient email.
8. Test the workflow and activate it when everything works correctly.

## 🔐 Security Notice

- Never upload API keys, passwords, access tokens, or private credentials.
- Configure your own credentials inside n8n.
- Replace the placeholder RSS URL and email address before execution.

## 🎯 Learning Outcomes

- Understanding AI-powered workflow automation.
- Working with RSS feeds.
- Integrating Google Gemini with n8n.
- Building automated reporting systems.
- Understanding practical applications of Generative AI.

## 👨‍💻 Author

**Vedanth G T**

BCA Student | Aspiring Software Developer | Generative AI Enthusiast

- GitHub: [CodeWithVedanth](https://github.com/CodeWithVedanth)
- LinkedIn: [Vedanth G T](https://www.linkedin.com/in/vedanth-g-t-048581381)

---

⭐ If you find this project interesting, feel free to explore the repository!
