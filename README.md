# 🎥 RAG YouTube Chatbot using LangChain

A **Retrieval Augmented Generation (RAG)** based chatbot that allows users to ask questions about a **YouTube video** and receive **accurate, context-aware answers** using the video transcript.

This project uses **LangChain**, **FAISS**, and **LLMs (OpenAI / HuggingFace)** to build an end-to-end RAG pipeline.

---

## 🚀 Features
- 📄 Extracts YouTube video transcripts automatically
- ✂️ Splits long transcripts into manageable chunks
- 🧠 Converts text into vector embeddings
- ⚡ Stores embeddings in FAISS vector database
- 🔍 Retrieves relevant context using semantic search
- 🤖 Generates grounded answers using LLMs
- ❌ Prevents hallucinations (answers only from context)

---

## 🧱 Architecture (RAG Pipeline)

YouTube Video
↓
Transcript Extraction
↓
Text Chunking
↓
Embeddings Generation
↓
FAISS Vector Store
↓
Retriever (Top-K Similarity Search)
↓
Prompt Augmentation
↓
LLM Response


---

## 🛠️ Tech Stack
- **Python**
- **LangChain**
- **FAISS**
- **youtube-transcript-api**
- **OpenAI / HuggingFace LLMs**
- **Google Colab**

---

## 📦 Installation

```bash
pip install youtube-transcript-api langchain langchain-community \
            langchain-openai faiss-cpu transformers huggingface_hub


“This project implements a Retrieval Augmented Generation pipeline where YouTube transcripts are embedded, indexed, and retrieved to generate accurate, context-aware responses.”




