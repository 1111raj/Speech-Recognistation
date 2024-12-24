# Speech Recognition System 🎙️

## Overview
This project is a simple **Speech Recognition System** built using Python. It captures audio input through a microphone, processes it in real-time, converts speech to text, and provides audio feedback by speaking out the recognized text. The system leverages libraries like `SpeechRecognition` and `pyttsx3` to demonstrate basic speech-to-text and text-to-speech functionalities.

---

## Features
- **Real-Time Speech Recognition**: Captures and transcribes audio input using a microphone.
- **Text-to-Speech Conversion**: Provides audio feedback of the recognized text.
- **Noise Adjustment**: Dynamically adjusts to ambient noise for better accuracy.
- **Error Handling**: Handles unknown or unrecognized audio inputs gracefully.

---

## How It Works
1. The system listens to audio input using a microphone (`speech_recognition` library).
2. It processes the audio to adjust for ambient noise and recognize speech using Google's Speech Recognition API.
3. Recognized text is converted to lowercase and printed to the console.
4. The text is then converted back to speech using `pyttsx3` for audio feedback.

---

## Technologies Used
- **SpeechRecognition**: For capturing and processing audio input.
- **pyttsx3**: For text-to-speech conversion.
- **Python**: Core programming language for implementation.

---

## Requirements
- Python 3.x
- Libraries:
  - `speech_recognition`
  - `pyttsx3`

Install the required libraries:
```bash
pip install speechrecognition pyttsx3
