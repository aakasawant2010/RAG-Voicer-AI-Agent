# 🎙️ RAG Voice AI Agent

A real-time **Voice RAG AI Agent** that allows users to interact with an AI assistant using natural voice conversations.

The system combines **speech-to-text, RAG, LLM reasoning, and text-to-speech** to provide context-aware voice responses.

## 🚀 Tech Stack

- **Pipecat** – Real-time voice pipeline
- **VAD** – Voice activity detection
- **Deepgram** – Speech-to-text
- **Groq / Llama** – LLM
- **Gemini Embeddings** – Text embeddings
- **MongoDB Atlas** – Vector/database storage
- **ElevenLabs** – Text-to-speech
- **FastAPI** – Backend APIs
- **Docker** – Containerization

## 🏗️ Architecture

```text
User Voice
    ↓
Pipecat + VAD
    ↓
Deepgram STT
    ↓
RAG Retrieval
    ↓
Groq / Llama
    ↓
ElevenLabs TTS
    ↓
Voice Response
```

## ✨ Key Features

- Real-time voice interaction
- Retrieval-Augmented Generation (RAG)
- Context-aware AI responses
- Speech-to-text and text-to-speech
- Vector-based knowledge retrieval
- Containerized deployment

## 📁 Project Structure

```text
├── backend/
├── frontend/
├── infrastructure/
├── scripts/
├── .github/
├── docker-compose.yml
├── DEPLOYMENT.md
└── flow.excalidraw
```

## ⚙️ Setup

Clone the repository:

```bash
git clone https://github.com/aakasawant2010/RAG-Voicer-AI-Agent.git
cd RAG-Voicer-AI-Agent
```

Create your environment variables using `.env.example` and add the required API keys.

Then start the application using the provided Docker configuration:

```bash
docker-compose up --build
```

## 🔑 Environment Variables

Required credentials include:

```text
DEEPGRAM_API_KEY
GROQ_API_KEY
ELEVENLABS_API_KEY
GOOGLE_API_KEY
MONGODB_URI
```

## 📌 Purpose

This project demonstrates how **real-time voice AI and RAG** can be combined to build an intelligent conversational assistant.

---

**Built with Python, RAG, LLMs, and Voice AI.**
