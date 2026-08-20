# 🚀 VenJobBot — Automated Job Finder with n8n

An automated job monitoring workflow built with **n8n** that searches for the latest **Data Analyst jobs** across multiple locations in India, filters entry-level opportunities, and sends matching jobs directly to **Telegram**.

## 🎯 What Does It Do?

Searching for fresher jobs every day can be repetitive and time-consuming.

**VenJobBot automates the process.**

The workflow fetches recent Data Analyst job listings from the **Adzuna Job API**, filters opportunities suitable for freshers and entry-level candidates, and instantly delivers the results to a Telegram chat.

> **Search less. Apply faster. 🚀**

## ⚡ Features

- 🔍 Automatically searches for Data Analyst jobs
- 🇮🇳 Focused on selected locations in India
- 📍 Searches jobs from:
  - Kerala
  - Chennai
  - Bengaluru
  - Hyderabad
  - Coimbatore
- 🆕 Fetches recently posted jobs
- 🎓 Filters entry-level and fresher opportunities
- 🤖 Built completely using n8n automation
- 📱 Sends job details directly to Telegram

## 🧠 How the Workflow Works

```text
Manual Trigger
      │
      ▼
Fetch Jobs from Adzuna API
      │
      ▼
Split Job Results
      │
      ▼
Filter Entry-Level Jobs
      │
      ▼
Send Matching Jobs to Telegram
