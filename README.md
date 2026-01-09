
# 🤖 Jarvis AI – Python Voice Assistant

Jarvis AI is a Python-based voice assistant that performs various tasks using voice commands, such as searching Wikipedia, opening websites, playing music, telling jokes, fetching weather updates, reading news, and more.
It uses speech recognition and text-to-speech to interact with the user naturally.

---

## 🚀 Features

* 🎤 Voice command recognition
* 🗣️ Text-to-speech responses
* 📖 Wikipedia search and summary
* 🌐 Open popular websites (Google, YouTube, Amazon, Spotify, StackOverflow)
* ⏰ Current time announcement
* 🎵 Play local music
* 🎮 Launch applications (e.g., Valorant)
* 📰 Latest news reading
* ☁️ Weather & temperature updates
* 📸 Take photos using system camera
* 😂 Tell programming jokes
* 💬 Send WhatsApp messages
* 👋 Interactive greetings and responses
* 🛑 Voice-controlled program termination

---

## 🛠️ Technologies & Libraries Used

* **Python 3**
* `pyttsx3` – Text-to-speech
* `speech_recognition` – Voice input
* `wikipedia` – Wikipedia search
* `webbrowser` – Open websites
* `requests` – HTTP requests
* `BeautifulSoup` – Web scraping
* `pyjokes` – Jokes generation
* `pyautogui` – Keyboard & system automation
* `datetime`, `os`, `time` – System utilities

---

## 📂 Project Structure

```
Jarvis-AI/
│
├── main.py               # Main Jarvis AI program
├── wishme.py             # Greeting logic
├── NewsRead.py           # News fetching logic
├── whatsapp.py           # WhatsApp messaging feature
├── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/jarvis-ai.git
cd jarvis-ai
```

### 2️⃣ Install Required Libraries

```bash
pip install pyttsx3 SpeechRecognition wikipedia requests beautifulsoup4 pyjokes pyautogui
```

> ⚠️ Make sure your microphone is working properly.

---

## ▶️ How to Run

```bash
python main.py
```

Once started, Jarvis will greet you and begin listening for voice commands.

---

## 🎙️ Example Voice Commands

* “Search Wikipedia for Artificial Intelligence”
* “Open YouTube”
* “What is the time”
* “Play music”
* “Tell me a joke”
* “What’s the weather”
* “Take a photo”
* “Send WhatsApp message”
* “Sleep” / “End program”

---

## 🖥️ Platform Support

* Optimized for **Windows**
* Uses **SAPI5** voice engine
* Some features (camera, apps, paths) are **Windows-specific**

---

## 🧠 Future Enhancements

* GUI interface (Tkinter / PyQt)
* ChatGPT integration
* Dynamic weather by city
* Email sending feature
* Cross-platform support
* Hotword detection (e.g., “Hey Jarvis”)

---

## 📜 License

This project is for **educational purposes**.
You are free to modify and enhance it.

---
