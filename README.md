<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1a2e,100:e94560&height=120&section=header&text=Ankit%20Kumar&fontSize=42&fontColor=eaeaea&fontAlignY=65&animation=fadeIn" width="100%"/>

### Builder · AI Enthusiast · Computer Vision Nerd

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankit-kumar-10o26/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_.ken_k_/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ankitmukesh2003@email.com)

</div>

---

## 👋 About Me

I'm a self-driven developer who builds things at the intersection of AI, computer vision, and thoughtful software design. I care about projects that solve real problems — not just demos. Whether it's a face-authenticated vault, a gesture-controlled mouse, or a local RAG assistant, I build to learn and ship to grow.

- 🔭 **Currently building:** AI SecureVault — a desktop security app with face recognition + AES encryption
- 🌱 **Exploring:** LLMs, RAG pipelines, and local AI tooling
- 💬 **Ask me about:** OpenCV, Python system design, PyQt5, or anything computer vision
- ⚡ **Philosophy:** *"The only way to learn is to build."*

---

## 🛠️ Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Libraries & Frameworks**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![PyQt5](https://img.shields.io/badge/PyQt5-41CD52?style=flat-square&logo=qt&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![GTK](https://img.shields.io/badge/GTK4-4A86CF?style=flat-square&logo=gtk&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![PyInstaller](https://img.shields.io/badge/PyInstaller-3776AB?style=flat-square&logo=python&logoColor=white)

---

## 🚀 Projects

### 🛡️ AI SecureVault
> **Python · PyQt5 · face_recognition · dlib · Cryptography · SQLite**

A production-grade desktop security application combining multi-factor authentication and AES file encryption. Face recognition with liveness detection (eye blink) serves as the primary auth method, with bcrypt-hardened passwords as fallback. Vault keys are derived via PBKDF2-HMAC-SHA256 (480K iterations) and **never stored on disk** — only the salt persists.

- 🎭 Real-time face recognition with liveness (blink) detection
- 🔐 AES-128 Fernet encryption with session-bound, in-memory key
- 🚨 Intruder capture: unknown faces are photographed and logged with timestamps
- 📊 Full SQLite audit trail for all auth and encryption events
- 📦 Ships as a standalone `.exe` via PyInstaller

---

### 🧩 Crossword Puzzle Game
> **C · GTK4**

A desktop crossword puzzle game with a full GUI built in GTK. Features a Trie-based word engine, teacher/student roles, a word & hint database, and an access-controlled Teacher Menu for adding new words.

- Trie data structure for fast word lookup
- Role-based UI (Student / Teacher)
- Persistent word database via text file
- Auto-generated crossword grid from word pool

---

### 📄 DocMind AI — RAG Document Q&A
> **Python · LangChain · Ollama · ChromaDB · Tkinter**

A local RAG (Retrieval-Augmented Generation) application that lets you upload documents and ask questions about them using a locally running LLM.

- Supports PDF, DOCX, TXT, CSV, Markdown
- Chunking, embedding, and vector storage with ChromaDB
- Hot-swappable Ollama chat models
- Clean dark-themed Tkinter GUI with source attribution

---

### 🛡️ Face Recognition Security System
> **Python · OpenCV · Tkinter**

A real-time face recognition security system that uses OpenCV's LBPH algorithm to register and authenticate users via webcam.

- Register multiple users with live face capture
- Real-time recognition with confidence scoring
- Access log with GRANTED / DENIED history
- Face management (add / delete users)

---

### 🖐️ Hand Gesture Mouse Controller
> **Python · MediaPipe · TensorFlow · PyAutoGUI**

Control your computer mouse entirely with hand gestures captured via webcam — no hardware required.

| Gesture | Action |
|---|---|
| Palm | Move Cursor |
| Index finger | Left Click |
| Peace ✌️ | Right Click |
| Fist | Scroll |
| Thumb + Pinky | Double Click |
| OK 👌 | Click & Drag |

- MediaPipe landmark detection (63 features)
- Custom TensorFlow classifier trained on collected data
- Gesture smoothing with ring buffer for stability
- Data collection & training pipeline included

---

### 🌐 Custom New Tab Page
> **HTML · CSS · JavaScript**

A personalized browser new tab page themed around anime aesthetics.

- Live clock with date
- Google search bar
- Quick-access shortcut tiles (Anime, Manga, YouTube, etc.)
- Animated sidebar with Google apps
- Responsive design for mobile

---

### 🔢 Sudoku Game
> **HTML · CSS · JavaScript**

A fully functional browser-based Sudoku game with a polished UI.

- 3 difficulty levels (Easy / Medium / Hard)
- Dark mode toggle
- Save & continue game via localStorage
- Real-time error highlighting
- Animated win screen with time display

---

### 🎙️ VoiceFlow — AI Voice Assistant
> **Python · LangChain · Ollama · pyttsx3 · SpeechRecognition · Tkinter**

A local AI-powered voice assistant with a tool-calling agent loop. Speaks commands aloud,
transcribes your voice, and dispatches real system actions — entirely on-device.

- LangChain agent with `bind_tools()` loop — routes commands to the right tool automatically
- Opens websites, launches apps, searches Google/YouTube via voice
- Continuous **or** single-shot listening modes with ambient noise calibration
- Offline TTS via pyttsx3 with voice preference selection
- Hot-swappable Ollama models at runtime (supports cloud models like MiniMax, Kimi)
- Sliding conversation memory window for context-aware responses

---

## 📬 Connect

I'm always open to interesting project ideas, collaborations, or just a good tech conversation.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ankit-kumar-10o26/)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/_.ken_k_/)
[![Discord](https://img.shields.io/badge/Discord-Join%20Server-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.gg/WBBYCyJbrb)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:ankitmukesh2003@email.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-1a1a2e?style=flat-square&logo=vercel&logoColor=white)](https://ankitkportfolio.streamlit.app/)

---

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:e94560,100:1a1a2e&height=80&section=footer" width="100%"/>
</div>
