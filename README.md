# AI Portfolio — Learning Notes

A collection of hands-on AI projects built fro personal learning,
focused on LangChain, agentic AI, and production-ready ML systems.

## Projects

### 01 — LangChain RAG Basics
> `notebooks/01_langchain_rag_basics.ipynb`

A retrieval-augmented generation (RAG) chatbot built from scratch using 
LangChain and a local Ollama LLM. Covers document loading, text splitting, 
FAISS vector stores, and prompt engineering.

**Stack:** LangChain 1.2 · Ollama (llama3.1:8b) · FAISS · JupyterLab

### 02 — Conversation Memory & Chat History (in progress)
> `notebooks/02_langchain_memory.ipynb`

Extending the RAG chatbot with multi-turn conversation memory, 
query rewriting, and persistent chat history.

**Stack:** LangChain 1.2 · Ollama · FAISS

## Setup

```bash
git clone https://github.com/mutiinsani/ai-portfolio.git
cd ai-portfolio
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Environment

- Python 3.14.4
- Local LLMs via Ollama 
