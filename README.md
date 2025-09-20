# 📖 Complete RAG Pipeline with HuggingFace Embeddings  

## 🔹 Overview  
This project implements a **Retrieval-Augmented Generation (RAG) pipeline** with end-to-end functionality using **HuggingFace embeddings**.  
It demonstrates how to:  
- Ingest and preprocess text & PDF documents  
- Generate embeddings with HuggingFace models  
- Store and query vectors with a vector store (ChromaDB)  
- Retrieve relevant context for queries  
- Run everything via both **Jupyter Notebook** and **Python scripts**  

---

## ⚙️ Tech Stack  
- **Python 3.10+**  
- **HuggingFace Transformers** (for embeddings)  
- **ChromaDB** (vector store)  
- **LangChain** (RAG orchestration)  
- **VS Code / Jupyter Notebook**  

---

## 📂 Project Structure  
Complete-RAG/
│── data/                 # Input documents
│   ├── pdfs/             # PDF files
│   └── text_files/       # TXT files
│── vector_store/         # ChromaDB persistent store
│── notebook/             # Jupyter notebooks
│   └── document.ipynb
│── main.py               # Entry script
│── requirements.txt      # Dependencies
│── pyproject.toml        # Project config
│── README.md             # Documentation


---

## 🚀 Installation  

Clone the repo:  
```bash
git clone https://github.com/your-username/Complete-RAG-Pipeline.git
cd Complete-RAG-Pipeline

Example: 
rag_retriever.retrieve("What is attention in Transformers?")
