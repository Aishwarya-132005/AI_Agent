n8n AI Email Automation Agent

An AI-powered email automation workflow built using n8n, designed to categorize incoming emails and send Telegram notifications for approval-based actions.

This project was created as a learning and experimentation project by following and customizing concepts from YouTube tutorials and online resources.

---

Project Overview

The workflow automatically:

- Monitors incoming emails
- Categorizes them using AI
- Sends Telegram notifications with action choices
- Prepares for AI-generated automated replies

The goal of this project is to explore AI workflow orchestration, automation systems, and agent-based communication using low-code tools.

---

Features

- Email categorization using AI
  - Urgent
  - Collaborative
  - Customer Support
  - General Queries
- Telegram notifications for approval actions
- Modular workflow built in n8n
- AI integration using Groq
- Trigger-based automation flow

---

Current Status

⚠️ Project is currently under development and debugging.

Completed:

- Email monitoring workflow
- AI-based categorization
- Telegram notification integration

Planned:

- AI-generated email replies
- Auto-send reply functionality
- Improved workflow stability

Current Issue:

- Telegram bot notifications were previously working but are currently not functioning.
- The workflow needs debugging and reconnection of Telegram bot credentials/settings.

---

Tech Stack

- n8n
- Groq API
- Telegram Bot API
- Database Integration
- Generative AI

---

What I Learned

Through this project, I learned:

- Building automation workflows in n8n
- Integrating AI APIs into workflows
- Trigger/event-based automation
- Workflow orchestration concepts
- Telegram bot integrations
- Debugging automation pipelines

---

How to Use

1. Open your n8n instance.
2. Import the provided ".json" workflow file.
3. Configure:
   - Email credentials
   - Telegram Bot credentials
   - Groq API key
   - Database connection (if used)
4. Activate the workflow.
5. Test by sending an email to the configured inbox.

---

Note

This project was developed mainly for learning and experimentation purposes by implementing concepts from tutorials and modifying them with additional integrations and workflow logic.

The workflow is not fully production-ready and is currently being improved and debugged.
