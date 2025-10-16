# n8n Email Automation Agent

This project is an AI-powered email automation workflow built with n8n.  
It automatically categorizes incoming emails and sends Telegram notifications asking whether to reply, tweak, or cancel.  
The next phase will include generating and sending AI-based replies.

## Current Status
This project is in progress.  
Currently completed up to the Telegram notification stage.

## Features
- Categorizes incoming emails (Urgent, Collaborative, Customer Support, etc.)
- Sends Telegram alerts with action options
- (Planned) Generate and send AI-based replies

## How to Use
1. Open your n8n instance.
2. Import the provided `.json` workflow file.
3. Configure the email and Telegram nodes with your credentials.
4. Activate and run the workflow to test incoming emails.

## Tech Stack
- n8n
- Telegram Bot API
- database
- Generative AI (for upcoming reply automation)
