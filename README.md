# Telegram AI Chatbot

The workflow receives Telegram messages, processes them using an AI Agent powered by OpenRouter, and automatically sends intelligent replies back to the user.


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