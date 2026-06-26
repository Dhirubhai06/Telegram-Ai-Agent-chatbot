# Telegram-Ai-Agent-chatbot
Telegram AI Agent is an AI-powered chatbot built with n8n that automates conversations through the Telegram Bot API. It processes user messages, generates intelligent responses using AI, and demonstrates workflow automation, API integration, and scalable no-code/low-code development.
# 🤖 Telegram AI Agent with n8n

An AI-powered Telegram assistant built using **n8n** that automates conversations and productivity tasks. The workflow receives messages from Telegram, processes them with an OpenAI Chat Model, maintains conversation memory, and performs actions such as reading Google Sheets, creating Google Calendar events, and sending Gmail messages.

## 🚀 Features

- 💬 AI-powered Telegram chatbot
- 🧠 Context-aware conversations with memory
- 📅 Create Google Calendar events
- 📊 Read data from Google Sheets
- 📧 Send emails through Gmail
- ⚡ Automated workflow using n8n
- 🔒 Secure API integrations

## 🛠️ Tech Stack

- n8n
- Telegram Bot API
- OpenAI Chat Model
- Simple Memory
- Google Sheets API
- Google Calendar API
- Gmail API

## 📌 Workflow Architecture

```text
Telegram User
      │
      ▼
Telegram Trigger
      │
      ▼
AI Agent
 ├── OpenAI Chat Model
 ├── Simple Memory
 ├── Google Sheets Tool
 ├── Google Calendar Tool
 └── Gmail Tool
      │
      ▼
Send Response to Telegram
```

## 🔄 How It Works

1. User sends a message to the Telegram bot.
2. The Telegram Trigger captures the message.
3. The AI Agent processes the request using the OpenAI Chat Model.
4. Conversation context is maintained using Simple Memory.
5. Depending on the user's request, the AI Agent can:
   - Read data from Google Sheets
   - Create events in Google Calendar
   - Send emails via Gmail
6. The generated response is sent back to the user through Telegram.

## 📷 Workflow Screenshot

> Add the workflow image below.

![Workflow](workflow.png)

## 📂 Use Cases

- Personal AI Assistant
- Schedule meetings and reminders
- Read and manage spreadsheet data
- Send emails automatically
- Productivity automation
- Business workflow assistant

## ⚙️ Prerequisites

- n8n (Cloud or Self-hosted)
- Telegram Bot Token
- OpenAI API Key
- Google Cloud Project
- Google Sheets API
- Google Calendar API
- Gmail API

## 📥 Installation

1. Clone this repository.
2. Import the workflow into n8n.
3. Configure all credentials.
4. Activate the workflow.
5. Start chatting with your Telegram bot.

## 📜 License

This project is licensed under the MIT License.

---
