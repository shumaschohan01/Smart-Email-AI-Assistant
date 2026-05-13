AI-Powered Gmail Assistant & Classifier (n8n + Gemini)
An intelligent email management system built on n8n that automatically classifies incoming emails using Google Gemini AI and performs context-aware actions like drafting professional replies and organizing messages with custom labels.

🚀 Overview
This workflow transforms your Gmail into a self-organizing assistant. It monitors your inbox, understands the intent of the email using Natural Language Processing (NLP), and routes it through specialized AI agents to ensure every message is handled with a professional touch.

🛠 Features
Intelligent Classification: Uses a Text Classifier node to categorize emails into New Order, AI, Jobs, or Others.

Agentic AI Responses: Employs multiple AI Agents powered by Google Gemini to draft polite, professional, and concise replies.

Automatic Labeling: Seamlessly organizes your inbox by creating and applying labels based on the email's category.

Draft Automation: Automatically creates a response draft in Gmail for categorized emails, saving you hours of manual typing.

Cost-Efficient Logic: Designed to minimize API calls by routing traffic through specific logic branches.

🏗 Workflow Architecture
The workflow follows a structured logic path:

Trigger: Gmail Trigger polls for new emails every minute.

Analyze: The Text Classifier (linked to Gemini) identifies the email type based on the snippet.

Process: The email is routed to a specific AI Agent (e.g., Agent for AI tech, Agent for Job queries).

Action: * Creates a professional reply draft in Gmail.

Creates and assigns a relevant label (AI, Jobs, etc.) to the message.

📋 Prerequisites
n8n Instance: (Desktop, Cloud, or Docker version).

Google Gemini API Key: Obtainable from Google AI Studio.

Gmail Credentials: OAuth2 setup for Gmail API access within n8n.

🔧 Installation & Setup
Clone the Repository:

Bash
git clone https://github.com/shumaschohan1/Smart-Email-AI-Assistant.git
Import to n8n:

Open your n8n dashboard.

Go to Workflows > Import from File.

Select Free Gmail Classifier (Groq + Switch).json from this repository.

Configure Credentials:

Update the Gmail account credentials with your own OAuth2 details.

Update the Google Gemini (PaLM) Api account credentials with your Gemini API key.

Activate: Save and set the workflow to Active.

<img width="482" height="412" alt="image" src="https://github.com/user-attachments/assets/8d282c89-e261-4711-8c67-b4e3bf2b468e" />

🤝 Connect with Me
Agar aapko is project ke bare mein koi sawal ho ya aap collaboration chahte hon:

Developer: Shumas Kashif Chohan
LinkedIn: https://www.linkedin.com/in/shumas-kashif-chohan-54b51830b/
Email: shumaschohan0@gamil.com
