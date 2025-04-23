# Voice Assistant with OTP Email Verification 🔐🗣️

This Python project combines voice command recognition with email-based OTP verification. Users can interact with the assistant through speech to open websites, perform basic queries, and trigger email-based OTP authentication.

## 🔧 Features

- Voice recognition using `speech_recognition`
- Speech synthesis via `pyttsx3`
- Email-based OTP sending with `smtplib`
- Predefined voice responses and web navigation commands

## 📂 Project Structure

- `otp.py` – Sends OTPs via email for authentication.
- `speech.py` – Main script for the voice assistant that can handle commands and call OTP functionality.

## 🛠️ Installation

```bash
git clone https://github.com/AshokSai1999/Speech-Recognition
cd voice-assistant-otp
pip install pyttsx3 speechrecognition pyaudio

🚀 Usage
Run the voice assistant:
python speech.py

📦 Dependencies
pyttsx3
speech_recognition
smtplib
email (from Python stdlib)

👨‍💻 Author
Ashok Sudireddy

