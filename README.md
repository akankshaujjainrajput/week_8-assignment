# 🧠 RAG-based CSV Q&A Chatbot

This project is a **Retrieval-Augmented Generation (RAG)**-based chatbot that can **intelligently answer questions from uploaded CSV files** using:

- 📂 **CSV Document Parsing**
- 🧠 **Google Gemini API** (for Generative AI)
- 🔍 **Pinecone Vector DB** (for document search)
- 🧮 **Sentence Transformers** for embedding generation
- 💬 **Gradio** Interface for chat

---

## 🚀 Features

✅ Upload and index CSV files  
✅ Ask questions based on uploaded content  
✅ Embedding-based vector search  
✅ Context-aware response generation  
✅ Gradio-powered simple UI  
✅ Works in Google Colab (no local setup required)

---

## 🛠️ Tech Stack

| Component        | Tool/Service                |
|------------------|-----------------------------|
| Embeddings       | `all-MiniLM-L6-v2` (384-dim)|
| Vector DB        | [Pinecone](https://www.pinecone.io/) |
| LLM              | Google Gemini (`gemini-1.5-flash`) |
| Backend Logic    | Python, LangChain           |
| UI               | Gradio                      |
| File Types       | `.csv`                      |

---


