# ModelArena AI

A simple AI application that sends the **same prompt to two different LLMs** and displays their responses side by side.

## 🚀 How It Works

```text
User Prompt
     ↓
ModelArena AI
     ↓
 ┌───────────┬───────────┐
 ↓                       ↓
Model 1                 Model 2
 ↓                       ↓
Response 1              Response 2
 └───────────┬───────────┘
             ↓
      Compare Responses


✨ Features
Enter a single prompt
Send the same prompt to two LLMs
Compare responses side by side
Experiment with different models
Simple Gradio web interface
🛠️ Technologies
Python
OpenAI Python SDK
Groq API
Gradio
python-dotenv
📁 Project Structure
02-model-arena/
│
├── README.md
├── arena_app.py
├── requirements.txt
├── .env.example
└── screenshots/
    └── demo.png

⚙️ Setup
Install dependencies
pip install -r requirements.txt

Configure API key

Create a .env file:

GROQ_API_KEY=your_groq_api_key

Never commit .env or API keys to GitHub.

Run
python arena_app.py

Open the Gradio URL displayed in the terminal.

🎯 Purpose

This project is part of my hands-on AI Engineering journey, focused on understanding LLM APIs, model integration, prompt handling, and building practical AI applications.


