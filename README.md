# 📚 Chat With Your Documents

A **Retrieval-Augmented Generation (RAG)** application that allows users to upload PDF, DOCX, or TXT documents and ask questions about their content using natural language.

## 🚀 Features

* Upload PDF, DOCX, and TXT files
* Extract and chunk document text
* Generate embeddings and store them in ChromaDB
* Retrieve relevant document chunks using similarity search
* Generate grounded answers using Groq LLM
* Stream responses through Streamlit
* Display sources used for answers

## 🛠️ Tech Stack

**Python · Streamlit · LangChain · Groq · Sentence Transformers · ChromaDB**

## 🏗️ Project Structure

```text
docchat/
├── app.py              # Streamlit UI
├── config.py           # Configuration and prompts
├── file_loader.py      # Document loading
├── chunker.py          # Text chunking
├── vector_store.py     # Embeddings and retrieval
├── rag.py              # RAG prompt construction
└── llm.py              # Groq LLM integration
```

## 🔄 Workflow

```text
Upload Document
      ↓
Extract Text
      ↓
Chunk Text
      ↓
Generate Embeddings
      ↓
Store in ChromaDB
      ↓
Retrieve Relevant Chunks
      ↓
Generate Answer with Groq
```

## ⚙️ Setup

### 1. Install dependencies

```bash
pip install -r requirements.txt
```

### 2. Add your Groq API key

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

**Never upload your `.env` file or API key to GitHub.**

### 3. Run the application

```bash
streamlit run docchat/app.py
```

## 💡 Key Learning

This project demonstrates practical implementation of **document ingestion, text chunking, embeddings, vector search, RAG, prompt grounding, LLM integration, and Streamlit development.**

## 👩‍💻 Author

**Anukriti Srivastava**

