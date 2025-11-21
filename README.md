RAG DharmaBot 🕉️

A spiritual AI chatbot powered by Retrieval-Augmented Generation (RAG). DharmaBot provides answers, insights, and guidance from spiritual texts, teachings, and curated knowledge sources.

🌟 Overview

RAG DharmaBot is an AI assistant designed to offer spiritual learning, meditation guidance, and scriptural knowledge.
It uses vector embeddings + semantic search + LLM responses for accurate, context-aware answers.

✨ Features

🔍 Context-based spiritual Q&A

📚 Retrieval over uploaded spiritual documents

🧘 Guidance inspired by ancient teachings

🚀 Powered by Chroma DB, Sentence Transformers & LLM pipelines

🎨 User-friendly Streamlit interface

🛠️ Tech Stack

Python

Streamlit

ChromaDB

Sentence Transformers

Transformers (HuggingFace)

FAISS / Embedding-based Retrieval

📦 Installation
cd RAG_DharmaBot
python -m venv rag_env
rag_env\Scripts\activate   # (Windows)
pip install -r requirements.txt

▶️ Run the App
streamlit run app.py

📁 Project Structure
RAG_DharmaBot/
│── app.py
│── requirements.txt
│── knowledge_base/
│── utils/
│── embeddings/
│── README.md

📘 How It Works

User enters a question

Query is converted into embeddings

Relevant spiritual knowledge is retrieved

LLM generates a meaningful, spiritual response

Final answer shown in a clean UI
