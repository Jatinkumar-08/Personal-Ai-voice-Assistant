# Personal-Ai-voice-Assistant
This project is a voice-activated AI assistant, similar to Jarvis, Alexa, or Google Assistant, built using Python.
It supports voice recognition, AI responses, music playback, website control, and real-time news updates.

The assistant listens for the wake-word "Google", activates, and performs tasks based on your commands.

🚀 Features

🔊 Voice Recognition
Uses SpeechRecognition to listen through the microphone.
Detects the wake word: “Google”
Understands user commands through Google Speech API.

🧠 AI-Powered Responses
Uses OpenAI's GPT model for intelligent, conversational answers.
Short, smart responses similar to Alexa.

🌐 Opens Websites
Commands supported:
“Open Google”
“Open YouTube”
“Open Facebook”
“Open LinkedIn”

🎵 Music Player
Say “Play <song_name>”
Fetches the song link from your custom MySongLibrary.py

📰 Live News Reader
Uses NewsAPI to fetch top headlines.
Reads the news aloud via TTS.

🔈 Text-to-Speech Output
Uses gTTS (Google Text-to-Speech)
Plays audio using pygame

🧩 Error Handling
Gracefully handles microphone and API errors.

📂 Project Files
Voice-Assistant/
│── main.py
│── MySongLibrary.py
│── README.md
│── requirements.txt
