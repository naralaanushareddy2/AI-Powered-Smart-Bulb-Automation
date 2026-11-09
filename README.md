# 🤖 AI-Powered Smart Bulb Automation

## 📌 Project Overview

AI-Powered Smart Bulb Automation is an automation project that allows users to control a virtual bulb using natural-language commands. It uses an AI agent integrated with n8n, Groq, and ThingSpeak to understand user instructions and execute corresponding bulb operations.

## 🛠️ Technologies Used

- **n8n:** Workflow automation platform.
- **Groq API:** AI-powered command processing.
- **ThingSpeak:** IoT communication platform.
- **HTTP Methods:** GET and POST for API communication.
- **Session Memory:** Maintains conversational context.

## ✨ Key Features

- Control a virtual bulb using natural-language commands.
- AI-powered command understanding.
- Automated workflows using n8n.
- Integration with ThingSpeak for bulb control.
- HTTP GET and POST requests for communication.
- Session memory for maintaining conversation context.

## ⚙️ Workflow

1. User enters a command to turn the virtual bulb ON or OFF.
2. The AI agent processes the command.
3. The AI agent identifies the required action.
4. n8n executes the corresponding automation workflow.
5. ThingSpeak receives the HTTP request.
6. The virtual bulb performs the requested operation.

## 📂 Project Structure

```text
AI-Powered-Smart-Bulb-Automation/
│
├── workflow/
│   └── smart-bulb-workflow.json
│
├── screenshots/
│   └── workflow.png
│
└── README.md
```

## 🚀 How to Use

1. Download or clone this repository.
2. Import the JSON workflow into your n8n instance.
3. Configure your own AI model and ThingSpeak credentials.
4. Configure the required API connections.
5. Execute the workflow and interact with the AI agent.
6. Test the virtual bulb ON/OFF commands.

## 🔐 Security

- API credentials are not included in this repository.
- Users must configure their own credentials in n8n.
- Never share API keys or access tokens publicly.

## 👩‍💻 Author

**Anusha Narala**

- GitHub: [naralaanushareddy2](https://github.com/naralaanushareddy2)
- LinkedIn: [Anusha Narala](https://linkedin.com/in/anushanaral)