#🤖 SigmaGPT

SigmaGPT is an intelligent AI-powered chatbot platform built with Node.js, Express, and the OpenAI Chat API (gpt-4o-mini). It is designed to provide seamless and interactive user conversations through a simple API, which can be integrated into any frontend like React, Vue, or mobile apps.

#✨ Features
💬 AI Chatbot: Generate human-like responses using OpenAI’s GPT-4o-mini.

🌐 REST API: Simple and scalable Express API.

🔒 Environment-Based Configuration using .env.

🧠 Ready for AI Assistants: Use for study help, productivity tools, personal bots, etc.

⚙️ Modular Codebase: Easy to extend or plug into a larger app.

#🛠 Tech Stack
Backend: Node.js + Express.js

AI Model: OpenAI Chat API (gpt-4o-mini)

Storage (Optional): MongoDB (for logging chats or user history)

Libraries Used:

dotenv — environment variable management

cors — enable frontend communication

mongoose — for MongoDB (if used)

node-fetch — API calling

express — core framework

#🚀 Installation
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/Maddy398/SigmaGPT.git
cd SigmaGPT
2. Install Dependencies
bash
Copy
Edit
npm install
3. Create Environment File
Create a .env file in the root:

env
Copy
Edit
OPENAI_API_KEY=your_openai_api_key
MONGODB_URI=your_mongodb_uri   # optional, if you use MongoDB
4. Start the Server
bash
Copy
Edit
npm start
By default, the backend runs on:
http://localhost:8080

#📡 API Endpoint
POST /api/chat
Request Body:

json
Copy
Edit
{
  "message": "What is quantum physics?"
}
Response:

json
Copy
Edit
{
  "reply": "Quantum physics is the study of matter and energy at the most fundamental level..."
}

Embed in a study-assistant or productivity app

Add to an admin dashboard for smart AI help

#🤝 Contributing
We welcome contributions!

Fork the repo

Create a new branch: git checkout -b my-feature

Make changes & commit: git commit -m "Add feature"

Push: git push origin my-feature

Create a Pull Request
