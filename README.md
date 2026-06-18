# 🌍 Translingo — Multilingual AI Communication Tool

<p align="center">
  <b>Break language barriers with real-time translation + speech output</b><br>
  Built as a lightweight NLP-powered web application
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NLP-Translation-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Streamlit-WebApp-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/TTS-Audio-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/Focus-Global%20Communication-red?style=flat-square"/>
</p>

---

## 💡 What This Project Does

Translingo is a **real-time language translation system** that converts text into **100+ languages** and generates **audio output** for better accessibility.

👉 It transforms simple text into **multilingual, spoken communication**

---

## Demo Images

![demo](https://github.com/Tanmay1112004/Translingo/blob/main/screenshots/Screenshot%202025-08-24%20195604.png)

![demo](https://github.com/Tanmay1112004/Translingo/blob/main/screenshots/Screenshot%202025-08-24%20195704.png)

---

## 🚨 Problem Statement

In a global environment:

* Language barriers limit communication
* Text translation alone is not enough
* Accessibility (audio support) is often missing

👉 Result: Poor user experience in multilingual contexts

---

## 🎯 Solution

A unified application that:

✅ Translates text across multiple languages
✅ Converts translated text into speech
✅ Enables audio download for offline usage
✅ Provides a clean, fast, and user-friendly interface

---

## 🧠 System Workflow

```id="flow_trans"
User Input Text
      │
      ▼
Language Selection
      │
      ▼
Translation Engine (mtranslate)
      │
      ▼
Translated Text Output
      │
      ▼
Text-to-Speech (gTTS)
      │
      ▼
Audio Playback + Download
```

---

## ⚡ Key Features

### 🌍 Multi-Language Translation

* Supports **100+ languages**
* Fast and lightweight API-based translation

---

### 🔊 Text-to-Speech (TTS)

* Converts translated text into audio
* Improves accessibility
* Supports download functionality

---

### 🎨 Clean UI/UX

* Streamlit-based interface
* Minimal and intuitive design
* Sidebar-driven interaction

---

### ⚡ Real-Time Processing

* Instant translation
* Quick audio generation
* Smooth user experience

---

## 🛠 Tech Stack

| Layer              | Technology |
| ------------------ | ---------- |
| Language           | Python     |
| Frontend           | Streamlit  |
| Translation Engine | mtranslate |
| TTS                | gTTS       |
| Data Handling      | Pandas     |

---

## 📂 Project Structure

```id="struct_trans"
text-translator/
│
├── app.py
├── language.csv
├── requirements.txt
└── screenshots/
```

---

## 🚀 Run Locally

```bash id="run_trans"
git clone https://github.com//text-translator.git
cd text-translator
pip install -r requirements.txt
streamlit run app.py
```

---

## 🎯 Real-World Use Cases

* 🌍 Travel & tourism communication
* 🎓 Language learning tools
* 💬 Multilingual chat assistants
* ♿ Accessibility (audio-based output)
* 🏢 Global business communication

---

## 💼 What This Project Demonstrates

This project proves:

✅ NLP application development
✅ API integration (translation + TTS)
✅ UI + backend integration
✅ Real-time processing systems
✅ Product-focused thinking

---

## 🔮 Future Enhancements

* [ ] Speech-to-text input
* [ ] Real-time conversation mode
* [ ] Offline translation support
* [ ] AI-based contextual translation
* [ ] Mobile-responsive UI
* [ ] FastAPI backend deployment

---

## ⚠️ Disclaimer

Translation accuracy may vary depending on language and context.

---

## ⭐ Support

If you found this useful:

* ⭐ Star the repo
* 🍴 Fork it
* 🚀 Improve it

---

## 👨‍💻 Author

**Tanmay Kshirsagar**

---

## 🔥 Final Thought

Language is power.

👉 And tools like this make it **accessible to everyone.**
