# AI Voice Assistant for Customer Support

An AI-powered voice assistant system that handles customer queries through voice calls. The system simulates a basic telecom-style IVR support system using conversational AI and automated call workflows.

This project integrates voice APIs, NLP services, and automation tools to process user queries and generate responses in real time.

---

## Overview

This project demonstrates how voice automation and AI can be combined to build a simple customer support system. A user calls a phone number, the system processes the voice input using NLP, and then generates an appropriate response using AI.

The workflow connects multiple services including Plivo for call handling, Amazon Lex for speech processing, and GPT APIs for generating conversational responses.

---

## Features

- Voice-based interaction through phone calls
- Automated IVR-style call flow
- Natural language understanding using Amazon Lex
- AI-generated responses using GPT APIs
- Workflow automation using n8n
- Serverless processing using AWS Lambda

---

## Tech Stack

### Voice API
- Plivo

### AI / NLP
- Amazon Lex
- OpenAI GPT API

### Automation
- n8n

### Backend / Processing
- AWS Lambda
- Webhooks

---

## System Architecture

User Call  
↓  
Plivo receives the call  
↓  
Amazon Lex processes speech input  
↓  
Webhook triggers n8n workflow  
↓  
GPT API generates response  
↓  
Response returned to the user through voice  

---

## How It Works

1. A user calls the configured phone number.
2. Plivo handles the incoming call and receives the voice input.
3. Amazon Lex converts speech to text and identifies the intent.
4. n8n manages the workflow and sends the query to the GPT API.
5. GPT generates a conversational response.
6. The response is returned to the caller.

---

## Learning Outcomes

- Understanding voice API integration
- Building simple conversational AI systems
- Working with webhook-based automation
- Integrating multiple cloud services
- Designing IVR-style workflows

---

## Future Improvements

- Add support for multiple languages
- Improve conversation context handling
- Add analytics dashboard for call insights
- Deploy a more scalable backend architecture

---

## Author

**Animesh Srivastava**

Computer Science Student  
Jaypee Institute of Information Technology

GitHub: https://github.com/yourusername  
LinkedIn: https://linkedin.com/in/yourprofile
