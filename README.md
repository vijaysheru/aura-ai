# 🧘 Aurai – Voice-Based Wellness AI Assistant

> A multimodal AI agent for personalized wellness conversations using speech, memory, and large language models.  
> Currently in development — open to collaborators, testers, and feedback.

---

## 📌 Overview

**Aurai** is a voice-first AI assistant designed to help users manage stress, reflect on habits, and receive personalized wellness guidance — all through natural conversations.

Built on top of Whisper (for speech-to-text), GPT-4 (reasoning), and ChromaDB (persistent memory), Aurai acts as a mindful listener that remembers your voice and grows with your goals.

This project was initiated to explore how LLMs + RAG + emotion-aware prompts could create more humanlike, empathetic support tools — beyond chatbot UIs.

---

## 🎯 Use Case

- Daily check-ins for mood and mental health
- Voice-driven habit tracking and wellness reflection
- Stress journaling, goal reinforcement, and personalized feedback
- Private, secure, and offline-first AI assistant

---

## 🚧 Current Status

- 🧠 Whisper integration for speech-to-text complete  
- ✅ GPT-4 + LangChain reasoning pipeline built  
- ✅ RAG-enabled memory using ChromaDB (PDF/CSV uploads)  
- 🔐 AWS Lambda API deployment in testing  
- 🧪 Feedback loop + emotion prompts under experimentation

> 🎯 Target: Beta release for controlled feedback — **Q3 2025**

---

## ⚙️ Tech Stack

| Layer         | Tool / Framework |
|---------------|------------------|
| Speech Input  | Whisper (OpenAI) |
| LLM Backbone  | GPT-4 (OpenAI)   |
| RAG Memory    | LangChain + ChromaDB |
| Backend APIs  | FastAPI + AWS Lambda |
| Deployment    | Serverless / Local |
| Extras        | Coqui TTS (optional), Streamlit (for demo UI)

---

## 🧠 Features (Planned & Partial)

- [x] Real-time voice input with Whisper  
- [x] Personalized responses powered by GPT-4  
- [x] Persistent memory of user goals, history, and check-ins  
- [x] Document upload for custom health prompts (CSV/PDF)  
- [ ] Emotion-aware suggestion agent  
- [ ] Daily voice journaling log  
- [ ] Privacy mode (local-only, no logging)

---

## 🖼 Sample Prompt Flow

```text
User: "Aurai, I had a rough day. Feeling overwhelmed."
⬇️
→ Whisper transcribes speech
→ LangChain + GPT-4 generates:
"Aurai: I'm here with you. Want to take a few deep breaths or talk about what triggered it?"
⬇️
→ Response logged to memory and followed up later.
```

git clone https://github.com/vijaysheru/aurai-ai-voice-wellness
cd aurai-ai-voice-wellness
pip install -r requirements.txt

# Run locally (WIP)
streamlit run app.py
