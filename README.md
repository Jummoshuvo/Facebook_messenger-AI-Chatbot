# Facebook Messenger AI Chatbot

An **AI-powered Facebook Messenger chatbot** built with **n8n** and **Gemini API** for automated customer support and real-time responses.

---

## Features

- Automated responses to customer queries on Facebook Messenger
- AI-powered chatbot using **Gemini API**
- Workflow automation and orchestration via **n8n**
- Real-time messaging and context-aware replies
- Scalable and easy to extend for multiple services or FAQs

---

## Architecture Overview

1. **User Message** – Customer sends a message on Facebook Messenger.
2. **n8n Workflow** – Webhook captures the message and triggers the workflow.
3. **AI Processing** – Message is sent to Gemini API for AI-based response generation.
4. **Response Delivery** – AI-generated response is sent back to the user via Messenger.
5. **Optional Logging** – Responses and user messages can be stored for analytics.

---

## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Facebook_messenger_AI_Chatbot.git
