# Personal assistant Multi-Agent AI Automation System


---
## Project Overview
I developed a personal assistant multi-agent AI system that connects multiple tools and AI models to automate scheduling, task management, and chatbot interactions.

---

## Features & Workflow

-Telegram Chatbot Integration: Users can send both text and voice notes to a Telegram bot which then responds and also schedule & fetch tasks on google calender and also gets tasks from google to to list

-AI Processing Layer: Messages are processed by an AI agent powered by ChatGPT as the main model, with Gemini serving as a backup model.

-Google Calendar Automation: The system automatically creates and manages events on Google Calendar based on user input.

-Chained Workflows with n8n: Multiple workflows are connected in sequence, allowing one workflow to trigger another for continuous automation.

-Chat Interface Webhook: A web-based chatbot connected via a webhook enables real-time communication with the AI system, with was a prototype using bolt, to send message to m webhook, and then the webhooks recieves it processes it through the AI and then responds 

---

##Tech Stack
-n8n (Workflow Automation)
-ChatGPT and Gemini (AI Models)
-Google Tasks and Google Calendar APIs
-Telegram Bot API
-Webhooks Integration

---

##Result
The result is a fully automated AI system that listens, understands, and performs tasks across multiple platforms. It combines intelligent conversation, task scheduling, and automation into one cohesive solution.**
