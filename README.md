# 🌌 AuroraSkies Chatbot

<p align="left">
  <a href="https://colab.research.google.com/drive/1P7I3t3IV791BKLqfq_XZTbNCJpzWagDn?usp=sharing" target="_blank">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab"/>
  </a>
  &nbsp;&nbsp;
  <a href="https://t.me/AuroraSkiesBot" target="_blank">
    <img src="https://img.shields.io/badge/Chat%20with%20AuroraBot-telegram-blue?logo=telegram" alt="Chat with AuroraSkiesBot on Telegram"/>
  </a>
</p>


AuroraSkies Chatbot is a Retrieval-Augmented Generation (RAG) Telegram bot designed to answer airline FAQs with clarity, speed, and conversational flair. Built with TF-IDF, Hugging Face's Falcon-7B model, and Telegram API, it supports dynamic file uploads, automatic column detection, and robust error handling—perfect for real-world deployment and experimentation.

---

## 🚀 Features

- 🧠 TF-IDF-based FAQ retrieval with cosine similarity  
- 🤖 Falcon-7B text generation via Hugging Face pipeline  
- 📁 Dynamic CSV/XLSX upload and auto column detection  
- 💬 Telegram bot integration with real-time responses  
- 🔐 Secure token handling using Colab secrets  
- 🛠️ Modular, scalable, and beginner-friendly codebase

---

## 📦 Tech Stack

| Component         | Library/Tool               |
|------------------|----------------------------|
| Bot Framework     | `python-telegram-bot`      |
| Data Handling     | `pandas`, `scikit-learn`   |
| LLM Integration   | `transformers`, `huggingface-hub` |
| Secrets Management| `python-dotenv`, `userdata` |
| Async Execution   | `nest-asyncio`, `asyncio`  |
| Deployment        | Google Colab               |

---

## 🛠️ Setup Instructions

1. Open the Colab notebook above  
2. Upload your `airline_faq.xlsx` file when prompted  
3. Store your Telegram bot token in Colab secrets (`userdata`)  
4. Run the notebook and start chatting with AuroraBot on Telegram!

---

## 📌 Sample Prompt

```python
"You are AuroraBot, an airline assistant. Use the following relevant information to answer the question in a human-like, conversational manner..."
 the following relevant information to answer the question in a human-like, conversational manner..."
