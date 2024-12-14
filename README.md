# Jarvis_Python
A Simple Python project 
Overview
Jarvis is a Python-based voice assistant capable of recognizing speech and executing various commands. It can open and close applications, play YouTube videos, provide the current time, and respond to basic questions. The assistant is activated using the wake word "Jarvis".

Features
Voice Recognition:
Detects the wake word "Jarvis" to activate the assistant.
Listens for and executes commands.
Text-to-Speech:
Provides vocal feedback using the pyttsx3 library.

Command Execution:
Open Applications: Opens software like Google Chrome, Microsoft Edge, Notepad, and Calculator.
Close Applications: Closes the aforementioned software.
Play YouTube Videos: Plays videos on YouTube using the pywhatkit library.

Time Query: Tells the current time.
Custom Responses:
Responds to specific queries like "Who is God?" or "What is your name?"

Program Termination:
Stops running when the user says "stop."

Prerequisites
To run the program, you need:
Python 3.x

Libraries:
speechrecognition
pyttsx3
pywhatkit
pyaudio (required for microphone input; installation may vary based on your system)

Install dependencies using:
pip install SpeechRecognition pyttsx3 pywhatkit pyaudio

How to Run
Save the code in a file named jarvis.py.
Open a terminal or command prompt and navigate to the directory containing the file.
Run the script using:
python jarvis.py
Say the wake word "Jarvis" to activate the assistant, followed by your command.
