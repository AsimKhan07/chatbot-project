# 🎙️ Voice-Enabled Chatbot using NLTK, SpeechRecognition, and Pyttsx3

This project is a real-time, voice-interactive chatbot built using **Python**, with speech recognition and text-to-speech capabilities. It allows users to speak to the chatbot and receive spoken responses, enabling hands-free, natural language interaction.

## 🚀 Features

- 🗣️ **Speech to Text**: Converts spoken input into text using SpeechRecognition.
- 🧠 **Text Processing and Response**: Uses `NLTK` (Natural Language Toolkit) to analyze and generate responses.
- 🔊 **Text to Speech**: Speaks back the response using `Pyttsx3`, a TTS library for Python.
- ⏱️ Real-time interaction with minimal delay.
- 👨‍💻 Easy-to-understand Python code suitable for beginners in AI and NLP.

## 🛠️ Technologies Used

- **Python**: Core programming language.
- **NLTK**: Natural Language Toolkit for simple chatbot logic and text handling.
- **SpeechRecognition**: For capturing and converting user voice input into text.
- **Pyttsx3**: Offline text-to-speech conversion for speaking responses back.

## 📁 Project Structure

├── Working_chatbot.ipynb # Jupyter notebook with full implementation
├── README.md # Project documentation

markdown
Copy
Edit

## 🧑‍💻 How It Works

1. **Listen**: The bot listens to your voice through the microphone.
2. **Recognize**: Speech is converted to text using Google’s Speech Recognition API.
3. **Respond**: The text is passed to a basic NLTK logic for crafting a response.
4. **Speak**: The bot speaks back the response using Pyttsx3.

## ▶️ Getting Started

### Prerequisites

Install the required libraries:


pip install nltk SpeechRecognition pyttsx3 pyaudio
Run the Chatbot
You can run the chatbot by executing the notebook: Working_chatbot.ipynb.

Make sure your microphone is working and accessible.

📌 Notes
This chatbot uses simple rule-based response logic via NLTK and is ideal for educational purposes.

SpeechRecognition requires an internet connection for Google's API.

🧠 Future Improvements
Integrate with GPT or Transformer-based models for more intelligent replies.

Add GUI for better user experience.

Improve context handling and memory of previous conversations.

📄 License
This project is open-source and available under the APACHE License.

