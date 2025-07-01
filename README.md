# AI-Voice-Assistant
A simple Python-based AI voice assistant that responds to your voice and performs web tasks.
# 🎙️ Python Voice Assistant (Open Source)

A simple voice assistant project built with Python. This program listens for a keyword (default: "assistant") and performs tasks such as:

- Playing YouTube videos
- Searching on Google or YouTube
- Reading latest news headlines
- Opening popular websites
- Responding with speech

---

## ✅ Features

- **Voice Activation** using any keyword (e.g., "assistant", "jarvis", "professor")
- **Text-to-Speech** feedback
- **Speech Recognition**
- **News Headlines** using NewsData API

---

## 📦 Requirements

Install all dependencies using:

```bash
pip install pyttsx3 pywhatkit SpeechRecognition newsdataapi

Also install PyAudio (for microphone access):
# Windows
pip install pyaudio

# Linux
sudo apt install portaudio19-dev python3-pyaudio
pip install pyaudio

🔐 News API Setup
Sign up at https://newsdata.io/ to get your API key

Replace this line in the code:
newsapi = NewsDataApiClient(apikey='your_api_key_here')

🚀 How to Use
1. Set the ACTIVATION_NAME at the top of voice_assistant.py:
ACTIVATION_NAME = "assistant"
2. Run the program:
python voice_assistant.py
3. Say your activation name, and then give commands like:

"Search electric cars on Google"

"Play lo-fi music on YouTube"

"Give me the news"

"Open LinkedIn"

"Quit"
"

💡 Tips

Ensure a quiet environment for better speech recognition.

Make sure your microphone is enabled and accessible.

📁 Project Structure
voice-assistant/
│
├── voice_assistant.py   # Main script
└── README.md            # Usage and setup guide

🤝 Contributing
You can fork and improve this voice assistant. If you add cool features like weather, reminders, or smart home controls, share them via Pull Requests!

🧠 Built with Python — By Muhammad Mohsini Yousafi. Customize and enjoy! 

Ready to upload!



