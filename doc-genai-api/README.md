# 📚 doc-genai-api: Smart Document Q&A API

This project is a FastAPI-based backend for querying your own documents using LLMs like GPT-4. It implements Retrieval-Augmented Generation (RAG) with a PostgreSQL vector store (via `pgvector`) and uses LangChain for orchestration.

## 🚀 Features
- Upload PDFs and extract text
- Chunk documents and store embeddings in pgvector
- Query using natural language, answered via GPT-4 with RAG
- FastAPI endpoints for uploading, embedding, and querying
- Containerized with Docker
- Cloud-friendly and production-ready

## 🛠️ Tech Stack
- FastAPI ⚡
- LangChain 🦜🔗
- PostgreSQL + pgvector
- OpenAI API
- Docker

## 📦 Run Locally

```bash
pip install -r requirements.txt
uvicorn doc_genai.main:app --reload
