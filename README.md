# 📄 RAG-Based PDF Chatbot

An AI-powered chatbot that allows users to upload a PDF and ask questions about its content using Retrieval-Augmented Generation (RAG).

---

## 🚀 Overview

This project implements a complete **RAG (Retrieval-Augmented Generation)** pipeline that:

* Reads PDF documents
* Splits text into chunks
* Converts text into embeddings
* Stores embeddings in a vector database
* Retrieves relevant context for a query
* Generates answers based on the retrieved content

---

## 🧠 Key Features

* 📄 Upload and process PDF documents
* 🔍 Semantic search using vector embeddings
* 🤖 Context-aware question answering
* ⚡ Fast retrieval using FAISS
* 💬 Natural language interaction

---

## 🏗️ Tech Stack

* Python
* LangChain
* FAISS (Vector Database)
* HuggingFace Transformers
* Sentence Transformers (Embeddings)

---

## 🔄 Architecture

User Query → Embeddings → Vector Search → Retrieve Relevant Chunks → LLM → Answer

---

## ⚙️ How It Works

1. Load PDF using PyPDFLoader
2. Split text into smaller chunks
3. Convert chunks into embeddings
4. Store embeddings in FAISS vector database
5. Retrieve top relevant chunks for a query
6. Pass context to language model
7. Generate final answer

---

## 📦 Installation

```bash
pip install langchain langchain-community langchain-text-splitters faiss-cpu sentence-transformers transformers pypdf
```

---

## ▶️ Usage

1. Upload a PDF file
2. Run the notebook or script
3. Ask questions like:

   * "What is bias-variance tradeoff?"
   * "Explain RAG"
   * "Summarize this document"

---

## 📌 Example

**Input:**
What is bias variance tradeoff?

**Output:**
Bias is error due to incorrect assumptions (underfitting), while variance is error due to sensitivity to training data (overfitting). The goal is to balance both.

---

## 🎯 Applications

* Document Q&A systems
* AI-powered study assistant
* Resume analyzer
* Knowledge base chatbot
* Customer support automation

---

## 🚧 Future Improvements

* Streamlit UI for better interaction
* Chat history (memory)
* Multi-PDF support
* Better LLM integration (OpenAI / Mistral)
* Deployment on cloud

---

## 🧑‍💻 Author

Melwin

---

## ⭐ Acknowledgements

Inspired by modern LLM and RAG architectures used in production AI systems.
