# calendar-manager-bot

AI-powered Telegram bot for managing Google Calendar events using natural language.

## Features
- Create calendar events from Telegram
- AI-powered event extraction
- Google Calendar integration
- Automatic Telegram replies
- Memory-enabled conversations

## Setup

```bash
docker run -it --name n8n \
-p 5678:5678 \
-e WEBHOOK_URL=https://YOUR_DOMAIN \
n8nio/n8n
```

## Example

```text
Schedule meeting tomorrow at 5 PM
```

## Workflow

```text
Telegram → AI Agent → Google Calendar → Telegram Reply
```

