# Voicemail System

A Python-based voice messaging platform that enables secure user authentication, contact management, and the ability to send and receive voice messages via a TCP server-client model.

## 🧩 Overview

This desktop application simulates a voicemail service with core functionalities such as login/signup, managing contacts, recording messages, and playing received voicemails. It uses Python libraries such as `pyaudio` for audio capture and `simpleaudio` for playback, with a Tkinter GUI for user interaction.

## 🛠 Technologies Used

- Python
- Tkinter (GUI)
- pyaudio (Voice recording)
- simpleaudio (Playback)
- socket (TCP communication)
- SQLite (Local database)

## 🚀 Key Features

- 🔐 **Database Operations**  
  User registration, login authentication, and metadata storage for voicemails.

- 🔁 **Server-Client Communication**  
  The server listens on `127.0.0.1:12345`, and the client sends and receives `.wav` files representing voicemails.

- 🎙 **Audio Recording & Playback**  
  Uses `pyaudio` to record messages and `simpleaudio` to play them. Messages are saved in `.wav` format for portability and quality.

- 🖥 **Graphical User Interface**  
  GUI includes:
  - Login/Signup windows  
  - Contact list display  
  - Buttons for sending, receiving, and listening to voicemails

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AbdelrahmanAhmed240/Voicemail_System.git
