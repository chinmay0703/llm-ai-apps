# 📱 WhatsApp Chat Analysis with Llama 3.2 & Streamlit

![Watsapp Chat Analysis Demo](demo.gif)

This is an interactive chat analytics dashboard built using **Streamlit**, **Python**, and **Llama 3.2** (via Ollama API). It allows users to upload WhatsApp chat exports and automatically generate insightful analytics — including participant behavior, emoji use, weekday activity, sentiment analysis, and more.

---

## 🚀 Features

- 📂 Upload and analyze WhatsApp chat `.txt` file
- 📊 Visual statistics: daily activity, focus, emoji usage, heatmaps
- 📈 Calculates average response times, message frequency, and emoji usage
- 🧠 Asks LLM (Llama 3.2) complex questions about the chat
- 😄 Sentiment & emotion breakdown
- 🕵️ Detects who talks more, who starts conversations, and who ends them

## 📚 Libraries & Their Purpose

Library	Purpose

1) streamlit	UI framework to build interactive dashboards
2) requests	Sends requests to the Ollama API for LLM responses
3) tempfile	Handles temporary file storage for uploaded chat file
4) os	File system operations (e.g., removing temp files)
5) tiktoken	Tokenizer to count tokens in input text
6) datetime	Time parsing and formatting
7) re	Regular expressions to parse WhatsApp chat format
8) matplotlib	Basic visualizations (bar chart, pie chart)
9) seaborn	Advanced visualizations (heatmaps)
10) collections.Counter	For word, emoji, and sentiment counting
11) random	Used for simulating sentiment categories (placeholder)

---

## 🛠️ How to Run the Project

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/watsapp_chat_analysis.git
   cd watsapp_chat_analysis
