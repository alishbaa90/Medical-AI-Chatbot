# 🩺 Medical AI Chatbot

An AI-powered **Medical Chatbot** that answers general health and wellness queries using **Groq's LLaMA 3 model (`llama3-8b-8192`)**. Built on **Google Colab** with a simple **Streamlit** interface — no backend or frontend setup required. Just run the notebook and start chatting!

---

## 🚀 Features

- 💬 Chatbot interface built with **Streamlit**
- 🧠 Uses **Groq’s LLaMA 3 model (llama3-8b-8192)** for ultra-fast responses
- 📄 Just upload the `.ipynb` file and run — no installation required
- 🌐 Responds to medical & health-related questions instantly
- 🔐 Local session — no data stored or shared

---

## 🛠️ Technologies Used

- 🧠 [Groq LLaMA 3 (`llama3-8b-8192`)](https://groq.com/)
- 🧱 [LangChain](https://www.langchain.com/)
- 🎈 [Streamlit](https://streamlit.io/)
- 🐍 Python 3 (via Google Colab)

---

## ▶️ How to Run and Use

1. **Download or open the provided `.ipynb`** file (Colab notebook).

2. Open it in **[Google Colab](https://colab.research.google.com/)**.

3. Set your **Groq API key** in the notebook:
   ```python
   import os
   os.environ["GROQ_API_KEY"] = "your_api_key_here"
