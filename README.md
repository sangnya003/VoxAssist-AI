VoxAssist AI is a Python-based voice-controlled desktop assistant integrated with the OpenAI API. It converts speech to text, processes voice commands, generates AI-powered responses, and performs system-level actions such as opening websites and applications.
The project also includes a standalone OpenAI API test script for generating structured text responses (e.g., emails).

Project Overview 
This project demonstrates:
Speech-to-text conversion using Google Speech Recognition
AI-generated conversational responses using OpenAI
Command-based desktop automation
Basic runtime chat memory
OpenAI API integration via Python
It is designed as a hands-free assistant capable of executing commands and interacting conversationally.

Features :
Voice Assistant
Continuous voice listening
Speech recognition (English – India)
Open websites (YouTube, Google, Wikipedia)
Launch local applications
Time announcement
Chat reset functionality
AI-based conversational replies

OpenAI API Test Module :
Sends prompt to OpenAI model
Generates structured responses (e.g., resignation email)
Displays full JSON API response
Demonstrates token usage and model output handling

Tech Stack :
Python 3.8+
SpeechRecognition
PyAudio
OpenAI Python SDK
Webbrowser
OS module
Datetime

Installation 
Clone the repository :
git clone <your-repo-url>
cd VoxAssist-AI

Install dependencies :
pip install openai SpeechRecognition pyaudio numpy
Create config.py
apikey = "your_openai_api_key"

Run Voice Assistant :
main.py

Run OpenAI Test Script :
python openaitest.py

Example Commands
"Open YouTube"
"Open Google"
"What is the time"
"Using artificial intelligence..."
"Reset chat"
"Jarvis Quit"

Disclaimer
This project is for educational and demonstration purposes. It uses external APIs and system commands. Use responsibly.
