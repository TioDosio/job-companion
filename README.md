# 🚀 JobSearch AI Companion – Browser Extension

Your smart assistant for finding job opportunities, understanding roles, optimizing your CV/cover letter, and keeping track of every position you apply for — all in one place.

---

## ✨ Features

### 🔍 **Job Insights on Any Page**
When you visit a job posting, the extension analyzes the content and gives you:
- 💼 **Role summary**
- 💰 **Estimated salary range**
- 🧩 **Required skills & key responsibilities**
- 🏆 **Important keywords** to include in your CV and cover letter

### 🤖 **AI-Powered Companion**
Powered by the ChatGPT API (or any compatible LLM API), the AI:
- ✏️ Suggests **CV bullet points** tailored to the job
- 📨 Generates a **personalized cover letter**
- 📊 Provides **competitiveness insights** and how well you match the role

### 📚 **Application Tracker**
Never lose track of where you applied:
- ✔️ Save each job with one click
- 📅 Store status updates (applied, interview, rejected, etc.)
- 🔗 Sync automatically with **Google Sheets** for a portable database
- 📁 Use the Sheet as a dashboard for filtering & analytics

### ☁️ **Cloud Sync**
Your application history is stored in a connected Google Sheet:
- 🔄 Accessible from any device
- 🔐 You own all your data
- 🧩 Easy to export, analyze, or connect to other tools

---

## 🧱 Architecture Overview

```text
Browser Extension
      │
      ├── Content Script → Reads job posting & extracts text
      │
      ├── Background Script → Handles logic & API calls
      │
      ├── ChatGPT/LLM API → Provides job insights & writing help
      │
      └── Google Sheets API → Stores job applications

## 🛠️ Tech Stack

- Browser extension APIs (Chrome / Firefox / Edge)

- JavaScript / TypeScript

- ChatGPT API / OpenAI API

- Google Sheets API

- (Optional) Firebase or Supabase for additional storage

## 🎯 Roadmap

- 🔐 OAuth login with Google

- 🧠 Smart “match score” for each job

- 🎨 UI panel redesign

- 📝 CV keyword analysis upload tool

- 📊 Google Sheets dashboard templates

- 🌐 Support for multiple job boards

- 📦 Publish on Chrome Web Store

- 🤝 Contributing

## Contributions are welcome! Feel free to open Issues or PRs for features, bugs, or ideas.

### 📄 License

- MIT License — free to use, modify, and distribute.


Want me to add screenshots, badges, a logo, or installation instructions?
