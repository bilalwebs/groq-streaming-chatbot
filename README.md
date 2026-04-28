# 🚀 Advanced Groq-Powered AI Chatbot (with Memory)

A sophisticated, real-time AI assistant built using the **Llama-3.3-70b** model via Groq's high-speed inference engine. This chatbot features **persistent memory** (JSON-based) and a professional streaming UI.

---

## ✨ Key Features

- ⚡ **Ultra-Fast Inference:** Powered by Groq's LPU technology for near-instant responses.
- 🧠 **Persistent Context:** Remembers user details (like names) even after restarting the session using `memory.json`.
- 🌊 **Real-Time Streaming:** Smooth, token-by-token "human-like" typing effect with cursor support.
- 🛠️ **Robust Architecture:** Handles chat history safely and uses environment variables for security.
- 🎨 **Responsive UI:** Built with Gradio for a clean, mobile-friendly interface.

---

## 🛠️ Tech Stack

- **Language:** Python
- **LLM:** Llama-3.3-70b (via Groq Cloud)
- **UI Framework:** Gradio
- **Storage:** JSON (Local Persistence)

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/bilalwebs/groq-streaming-chatbot.git](https://github.com/bilalwebs/groq-streaming-chatbot.git)
cd groq-streaming-chatbot
