# 🧠 RAG Application with Gemini AI, LlamaIndex & Pinecone

This project implements a **Retrieval-Augmented Generation (RAG)** pipeline using:
- 🔮 **Gemini AI** (as the large language model)
- 📚 **LlamaIndex** (for document parsing, chunking, retrieval, and orchestration)
- 📦 **Pinecone** (as the vector database to store and retrieve embeddings)

---



This app allows you to:
- Load and index documents from a folder (e.g., `data/`)
- Split documents into semantically meaningful chunks
- Generate vector embeddings using Hugging Face models
- Store and retrieve those embeddings using **Pinecone**
- Query your documents with **Gemini AI** to produce accurate, grounded answers

---


| Component        | Library / Service           |
|------------------|-----------------------------|
| LLM              | Gemini AI (via API)         |
| Framework        | LlamaIndex                  |
| Embedding Model  | Sentence Transformers (`all-MiniLM-L6-v2`) |
| Vector Store     | Pinecone                    |
| Doc Loader       | LlamaIndex’s `SimpleDirectoryReader` |
| Language         | Python                      |
| Interface        | Jupyter Notebook / Script   |



