Chatbot Using LangChain and Gemini 2.0

This repository contains the implementation of a **CTSE Lecture Notes Chatbot** developed as part of the SE4010 – Current Trends in Software Engineering course at SLIIT.

## 📄 Description

The chatbot uses **Retrieval-Augmented Generation (RAG)** to answer questions based on PDF lecture notes. It is implemented using:
- LangChain
- Gemini 2.0 Flash Lite (via Google Generative AI API)
- ChromaDB for vector storage
- PyPDFLoader and RecursiveCharacterTextSplitter

The goal is to enhance learning by providing **citation-based answers** grounded in course material.

## 🧠 Model Choice

- **LLM Used**: Google Gemini 2.0 Flash Lite
- Chosen for: lightweight, fast response, good academic performance

## 🛠 Development Highlights

- Uses LangChain chains for RAG pipeline
- Custom prompts with source citations ([Page: X])
- Chunk size: 1000 characters with 100 overlap
- API usage optimized with top-k = 4

## 📂 Files Included

- `chatbot.ipynb`: Jupyter Notebook with full code
- `chatbot.pdf`: Project report with architecture, justification, and references

## 🔗 External Resources

- [LangChain RAG Tutorial](https://python.langchain.com/docs/tutorials/rag/)
- [Gemini Python SDK](https://github.com/google/generative-ai-python)
- [Chroma Documentation](https://docs.trychroma.com/)

## 🎥 Video Demonstration

📽️ [Click here to watch demo](https://drive.google.com/file/d/1fOuJUq7KC71K25wbU4o9emjEre_QxgjS/view?usp=drive_link)

## 📓 Jupyter Notebook Preview

🧪 [Notebook Preview Link](https://drive.google.com/file/d/1ZkSpIBbJLcFXmvbXfvCXMP6S2CKTubhC/view?usp=drive_link)

---

© 2025 – Samarasinghe V.R.  


