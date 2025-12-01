# 🎓 AI-Powered WhatsApp Assistant (Scholarships)

A self-hosted, full-stack automation system designed to handle student scholarship inquiries via WhatsApp. It utilizes **Google Gemini 1.5 Flash** for reasoning and integrates with **Notion** and **Google Sheets** as a dynamic knowledge base (RAG).

![Workflow Diagram](workflow-diagram.png)

## ✨ Key Features

- **🧠 RAG System (Retrieval-Augmented Generation):** The AI Agent retrieves scholarship details (requirements, links, degrees) directly from a **Notion Database** to answer queries accurately without hallucination.
- **💾 Context Awareness:** Uses **Google Sheets** to store user data and conversation history, allowing the bot to remember previous interactions.
- **🤝 Human-in-the-Loop (Hybrid Mode):** Includes a manual takeover mechanism. You can stop the bot for a specific user using the command `#stop` and resume automation with `#start`.
- **💸 Zero Cost Architecture:** Built using **n8n** and **Waha (WhatsApp HTTP API)** running on Docker, eliminating monthly per-message fees associated with official APIs.

## 🛠️ Tech Stack

- **Orchestration:** [n8n](https://n8n.io/) (Self-hosted)
- **WhatsApp API:** [Waha](https://github.com/devlikeapro/waha) (Dockerized)
- **AI Model:** Google Gemini 1.5 Flash
- **Database:** Google Sheets (User State) & Notion (Knowledge Base)

## 🚀 How to Use This Template

### 1. Prerequisites
You need **Docker** installed on your machine or VPS.

### 2. Start WhatsApp API (Waha)

### 3. Import to n8n

### 4.Fill needed credintials
