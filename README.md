# 📄 Doc-Assistant – Smart PDF Summarization & Q&A Generator

![GitHub Repo stars](https://img.shields.io/github/stars/manikanta2026/Doc-Assistant?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/manikanta2026/Doc-Assistant?style=flat-square)
![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat-square)


**Doc-Assistant** is an open-source web app that transforms long, complex PDFs into concise summaries and generates intelligent Q&A pairs — all powered by AI.

🚀 Perfect for students, researchers, and professionals who want to save time and extract insights fast.

---

## ✨ Features

- 📥 **PDF Upload & Processing**  
- 🧠 **Summarization Options**  
  - **Abstract** – Short and crisp  
  - **Summary** – Balanced and informative  
  - **Article** – Full-length overview  
- ❓ **Auto Q&A Generation**  
- 📋 **One-Click Copy**  
- 💻 **Modern UI** – Clean, responsive, and easy to use

---

## 🧪 Live Demo

👉 [Try it here](https://doc-assistant-frontend.vercel.app/)

## 🛠 Tech Stack

### Frontend
- ⚛️ React  
- 💨 Tailwind CSS  
- ⚡ Vite

### Backend
- 🐍 Flask  
- 📄 PyMuPDF  
- 🤖 Google Generative AI (Gemini)

---

## 🔧 Prerequisites

- Node.js (v16 or higher)
- Python (v3.8 or higher)
- Google API Key for Gemini

---

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/manikanta2026/Doc-Assistant

2. Install frontend dependencies
```bash
npm install
```

3. Install backend dependencies
```bash
cd backend
pip install -r requirements.txt
```

4. Create a `.env` file in the backend directory and add your Google API key:
```
GOOGLE_API_KEY=your_api_key_here
```

## ▶️ Running Locally

1. Start the frontend development server:
```bash
npm run dev
```
Start the backend server:
```bash
python backend/logic.py
```

The application will be available at `http://localhost:5173`

## 📘 Usage Guide

1. Upload a PDF document  
2. Choose a summary type: **Abstract / Summary / Article**  
3. Click **Summarize** or **Generate Q&A**  
4. Use the **Copy** button to save the results

## 🤝 Contributing

We welcome all contributions!  
If you have ideas or improvements, fork the repo and create a pull request. ⭐


## Live Website

https://doc-assistant-frontend.vercel.app/


