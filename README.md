# AI-Email-Automation-Workflow-n8n
An AI-powered email automation workflow built with n8n and Google Gemini that classifies incoming emails and automatically drafts or sends context-aware responses.


## Overview

This project demonstrates how AI can automate repetitive email management tasks using workflow orchestration and Large Language Models (LLMs).

The workflow continuously monitors incoming Gmail messages, classifies them into predefined categories, and uses Google Gemini to generate context-aware responses.

Depending on the email category, the workflow either:

- Creates an email draft
- Sends an automated response

The project showcases practical AI workflow automation using no-code/low-code tools.

---

## Workflow Highlights

- Gmail Trigger
- AI-Based Email Classification
- Google Gemini Integration
- Automatic Email Draft Creation
- Automated Email Replies
- Intelligent Routing
- End-to-End Workflow Automation

---

## Workflow Architecture

> *(Workflow Screenshot)*

![Workflow](screenshots/workflow.png)

---

## Workflow Process

```text
Incoming Gmail
        │
        ▼
 Gmail Trigger
        │
        ▼
 AI Text Classifier
        │
 ┌──────┴────────┐
 │               │
 ▼               ▼
Academic      Account
 │               │
 ▼               ▼
Gemini AI     Gemini AI
 │               │
 ▼               ▼
Draft Email   Send Email
```

---

## Features

- Automatically monitors Gmail inbox
- Classifies incoming emails using AI
- Uses Google Gemini to generate responses
- Creates Gmail drafts
- Sends automated replies
- Reduces manual email management
- Demonstrates AI workflow orchestration

---

## Tech Stack

- n8n
- Google Gemini
- Gmail API
- AI Text Classifier
- Workflow Automation
- Prompt Engineering

---

## Business Use Cases

- Student Email Assistant
- Customer Support Automation
- Internal Helpdesk
- Personal Email Management
- Business Email Automation

---

## Screenshots

### Complete Workflow
<img width="1600" height="771" alt="image" src="https://github.com/user-attachments/assets/aa2797b2-a6e5-4681-ba00-8aab1c0cc83f" />

---

## Future Improvements

- Support multiple email categories
- Calendar integration
- RAG-based response generation
- Multi-language support
- CRM integration
- Slack/Discord notifications

---

# ⚠ Note

This workflow was originally developed and tested using the free trial version of n8n.

The trial has since expired, so the live workflow is no longer accessible. This repository documents the workflow architecture, design, and implementation for portfolio purposes.

---

## Author

**Imara Asim**

Computer Science Student

COMSATS University Islamabad

---

## License

MIT License
