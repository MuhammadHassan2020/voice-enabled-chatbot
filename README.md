# Voice-Enabled AI Chatbot using Rasa 🎙️🤖

## 📌 Why I Made This Project
In an era of growing reliance on voice-driven technologies like Siri and Alexa, I wanted to explore the intersection of Natural Language Processing (NLP), conversational AI, and real-time voice interaction. This project aims to create a **browser-based voice assistant** that enables hands-free, intelligent conversations—providing an accessible and user-friendly solution for education, customer service, and daily assistance.

## 🌐 Project Overview
This is an end-to-end **Voice-Enabled Chatbot** built using **Rasa (NLP framework)** and **Web Speech API**, integrated with a custom JavaScript-based frontend and a high-performance backend using **Sanic**. The chatbot can:
- Recognize spoken queries via microphone 🎤
- Classify intents and manage dialogue using Rasa 📚
- Respond through text and convert it back to speech 🔊

## 💼 Business Problem
Typing long queries is inconvenient, especially for users who are visually impaired, multitasking, or using mobile devices. Businesses need:
- A fast and natural input method (voice)
- Scalable, intelligent assistants that can understand and respond accurately
- Cost-effective, open-source conversational solutions

## ✅ Solution
This project solves the above challenges by:
- Enabling **hands-free voice communication** via browser
- Using **Rasa** for flexible and accurate intent classification
- Implementing real-time interaction with minimal latency
- Supporting further expansion into domain-specific assistants (e.g., education, healthcare)

## 🛠️ Technologies Used
| Layer            | Tools/Frameworks                          |
|------------------|-------------------------------------------|
| Frontend         | HTML, CSS, JavaScript, Web Speech API     |
| Backend Server   | Python, Sanic (Async web server)          |
| NLP Core         | Rasa (DIETClassifier, RulePolicy, etc.)   |
| Voice Interface  | PyAudio (backend audio capture), Web APIs |
| Deployment Tools | Git, VS Code, Localhost (for testing)     |

## 🧠 Key Features
- Voice-to-text input and speech output
- 92%+ accuracy in intent recognition (30+ intents)
- Responsive web interface with real-time feedback
- Error handling and fallback responses
- Custom action support for dynamic replies

## 📈 Impact of the Project
- Enhanced accessibility for non-typers and visually impaired users
- Achieved under 1.2 seconds response time with async handling
- Delivered a scalable, modular chatbot architecture
- Gained real-world experience in NLP, full-stack development, and voice UI integration

## 🔮 Future Work
- Integrate advanced ASR models like Whisper or Vosk for improved voice recognition
- Add multilingual support and sentiment-based routing
- Improve noise filtering and optimize for mobile browsers
- Deploy via Docker with HTTPS and database integration
- Extend to domain-specific applications (e.g., medical assistant, student helpdesk)

---

## 🚀 Get Started (Local Setup)
```bash
# Clone the repo
git clone https://github.com/yourusername/voice-rasa-chatbot.git
cd voice-rasa-chatbot

# Install dependencies
pip install -r requirements.txt

# Start Rasa server
rasa run --enable-api

# Start action server (if using custom actions)
rasa run actions

# Start Sanic backend
python server.py

# Open index.html in browser
