VoxAssist AI
VoxAssist AI is a Python-based voice-controlled desktop assistant integrated with the OpenAI API. It converts speech to text, processes voice commands, generates AI-powered responses, and performs system-level actions such as opening websites and applications.
The project also includes a standalone OpenAI API test script for generating structured text responses (e.g., emails).

Project Overview 
This project demonstrates:
1 Speech-to-text conversion using Google Speech Recognition
2 AI-generated conversational responses using OpenAI
3 Command-based desktop automation
4 Basic runtime chat memory
5 OpenAI API integration via Python
It is designed as a hands-free assistant capable of executing commands and interacting conversationally.

Features :
1 Voice Assistant
2 Continuous voice listening
3 Speech recognition (English – India)
4 Open websites (YouTube, Google, Wikipedia)
5 Launch local applications
6 Time announcement
7 Chat reset functionality
8 AI-based conversational replies

OpenAI API Test Module :
1 Sends prompt to OpenAI model
2 Generates structured responses (e.g., resignation email)
3 Displays full JSON API response
4 Demonstrates token usage and model output handling

Tech Stack :
Python 3.8+
SpeechRecognition
PyAudio
OpenAI Python SDK
Webbrowser
OS module
Datetime

Installation :
1 Clone the repository
git clone <your-repo-url>
cd VoxAssist-AI

2 Install dependencies
pip install openai SpeechRecognition pyaudio numpy
Create config.py
apikey = "your_openai_api_key"

3 Run Voice Assistant
main.py

4 Run OpenAI Test Script
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
