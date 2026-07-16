# Telegram AI Chatbot

The workflow receives Telegram messages, processes them using an AI Agent powered by OpenRouter, and automatically sends intelligent replies back to the user.

## Features

- 🤖 AI-powered Telegram chatbot
- ⚙️ Built with n8n
- 🧠 OpenRouter LLM integration
- 💬 Automatic AI responses
- 🔧 Easy to customize

## Workflow Architecture

```text
┌──────────────┐
│ Telegram User│
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Telegram Bot │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ AI Agent     │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ OpenRouter   │
└──────┬───────┘
       │
       ▼
┌──────────────┐
│ Reply User   │
└──────────────┘
```
## Workflow Preview

![Workflow Overview](screenshots/workflow-overview.png)
