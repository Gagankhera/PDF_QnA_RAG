# 📘 PDF Query using RAG

A Retrieval-Augmented Generation (RAG) pipeline that allows you to **query PDF documents using natural language**.  
The system extracts text from PDFs, generates embeddings, stores them in a vector database, and retrieves the most relevant chunks to provide **accurate, context-aware answers** using an LLM.

---

## ✨ Features
- Upload PDF(s) and ask questions in plain English.
- Extracts and chunks text for efficient semantic search.
- Generates embeddings with transformer-based models.
- Stores and retrieves chunks using a vector database (FAISS / Chroma).
- Integrates with an LLM (OpenAI GPT or local models) for intelligent responses.

---

## 🛠 Tech Stack
- **Python**
- **LangChain / LlamaIndex** (for RAG pipeline)
- **Vector DB**: FAISS / ChromaDB
- **Embeddings**: SentenceTransformers / OpenAI Embeddings
- **LLM**: OpenAI GPT / Local model
- **Optional UI**: Streamlit / Gradio

---

## 🔄 Workflow
1. **Load & Parse PDF** → Extract raw text.  
2. **Chunking** → Split text into smaller segments.  
3. **Embedding Generation** → Create se
