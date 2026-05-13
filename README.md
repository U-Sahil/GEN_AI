#  AI News Summarizer using n8n & Google Gemini

An AI-powered automation workflow that fetches the latest AI and technology news from RSS feeds, summarizes them using Google Gemini, and delivers a structured daily tech brief directly through email.

---

##  Project Overview

This project uses **n8n workflow automation** and **Google Gemini AI** to automate the complete process of:

- Fetching AI & Tech news
- Aggregating RSS feed data
- Generating concise summaries using LLMs
- Categorizing news sections
- Sending automated email updates

The workflow runs automatically on a scheduled basis and delivers professional AI-generated news summaries.

---

##  Features

-  Automated AI & Tech News Fetching
-  AI-Powered Summarization using Google Gemini
-  Daily Email Delivery
-  Scheduled Automation using n8n
-  Prompt Engineered Structured Summaries
-  RSS Feed Integration
-  No Manual Work Required

---

##  Tech Stack

### Automation Platform
- n8n

### AI / LLM
- Google Gemini API

### Integrations
- RSS Feed Reader
- Gmail API

### Concepts Used
- Workflow Automation
- Generative AI
- Prompt Engineering
- API Integration
- Automated Scheduling

---

##  Workflow Architecture

```text
Schedule Trigger
      ↓
Fetch RSS Feeds (AI + Tech)
      ↓
Merge & Aggregate News Data
      ↓
Google Gemini AI Summarization
      ↓
Generate Structured News Brief
      ↓
Send Email via Gmail
