<h1 align="center">🎧 Media-Gen AI Speech Translator</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Flask-Web_App-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Whisper-AI-orange?style=for-the-badge"/>
</p>

---

## ✨ Overview

A powerful AI-powered web application that can:

- 🎙 Transcribe speech to text  
- 🌍 Translate text into multiple languages  
- 🔊 Convert translated text into speech (TTS)  
- 🎬 Process YouTube videos  
- 📁 Handle audio and video file uploads  
- 🎤 Record live voice input  

This project combines **speech recognition, translation, and text-to-speech** into a single seamless platform.

---

## 🚀 Features

<div style="display: flex; gap: 10px; flex-wrap: wrap;">

🧠 **AI Transcription**  
Uses OpenAI Whisper for accurate speech-to-text conversion  

🌐 **Translation Support**  
Supports multiple Indian and global languages  

🔊 **Text-to-Speech (TTS)**  
Generates natural voice using gTTS  

🎥 **YouTube Processing**  
Directly process audio from YouTube links  

📂 **File Uploads**  
Upload audio or video files easily  

🎤 **Live Recording**  
Record and process your voice instantly  

⚡ **Fast Flask Backend**  
Lightweight and efficient web server  

</div>

---

## 🛠 Tech Stack

- **Backend:** Flask (Python)
- **AI Models:** Whisper (Speech Recognition)
- **Translation:** Googletrans
- **TTS:** gTTS
- **Video Processing:** MoviePy
- **Audio Handling:** SoundFile
- **YouTube Processing:** yt-dlp
- **Frontend:** HTML, CSS, JavaScript

---

## 📸 UI Preview

> Clean and modern interface with:
- Gradient background  
- Responsive design  
- Interactive controls  
- Real-time output display  

---

## 📂 Project Structure
```
Media-Gen-AI/
│
├── app.py # Main Flask backend
├── index.html # Frontend UI
├── uploads/ # Temporary file storage
├── requirements.txt # Dependencies
└── README.md
```
---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Media-Gen-AI.git
cd Media-Gen-AI
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the app
```bash
python app.py
```

### 4️⃣ Open in browser
```bash
http://localhost:5000
```

---

## 🌍 Supported Languages
- English
- Hindi
- Bengali
- Tamil
- Telugu
- Kannada
- Malayalam
- Marathi
- Gujarati
- Punjabi
- Nepali
- Assamese

---

## 🧠 How It Works
1. User uploads audio/video or provides YouTube URL
2. Audio is extracted from the input
3. Whisper transcribes speech into text
4. Text is translated into the selected language
5. gTTS converts translated text into speech
6. Output is displayed and played in the browser

---   

## ⚠️ Limitations
- Heavy AI models may require high RAM
- Video processing can be slow
- Not optimized for free cloud hosting (memory limits)

---

## 💡 Future Improvements
- 🎯 Faster transcription models
- ☁️ Cloud-based AI API integration
- 🎥 Real-time video streaming support
- 🎨 Improved UI/UX
- 🌐 Multilingual voice output

---
  


