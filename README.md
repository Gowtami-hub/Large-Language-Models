
# RAG-based Stock Market Advisor using LLaMA 3.2 + Ollama + Streamlit

This project demonstrates how to build a local domain-specific assistant (stock market advisor) using LLaMA 3.2 with Retrieval-Augmented Generation (RAG). It includes:

- Document ingestion (PDFs)
- Semantic search using FAISS
- LLM querying using Ollama
- Streamlit interface for easy access

## How to Use

1. Start Ollama locally and pull the model:
```bash
ollama pull llama3.2
ollama run llama3.2
```

2. Install requirements:
```bash
pip install -r requirements.txt
```

3. Run Streamlit app:
```bash
streamlit run app.py
```

## Sample Documents
- Stock Market Fundamentals
- Tesla Outlook 2025
- Portfolio Strategy Guide
