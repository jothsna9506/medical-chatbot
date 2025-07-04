# medical-chatbot
# Medical Chatbot using OpenAI, Pinecone, LangChain, and Flask

A production-ready AI-powered medical chatbot that answers user queries related to diseases, diagnoses, medicines, and treatment suggestions. It leverages generative AI and a 637-page medical encyclopedia to provide accurate, context-aware, and reliable medical responses using semantic search and OpenAI’s large language models.

---

## Features

- Query understanding using OpenAI’s GPT-3.5/4
- Vector similarity search over 5,000+ medical text chunks
- Semantic embeddings generated via HuggingFace MiniLM
- Cloud-based vector store using Pinecone
- Reduced hallucinations through context-aware prompt engineering
- Interactive web interface built with Flask
- Modular Python codebase following best practices

---

## Tech Stack

### AI / NLP
- OpenAI GPT-3.5 / GPT-4
- Hugging Face MiniLM-L6-v2
- LangChain for retrieval-augmented generation (RAG)


### Vector Store
- Pinecone (cloud vector database)


### Backend
- Python
- Flask (API and web server)
- PyMuPDF (PDF text extraction)
- dotenv for environment configuration

### Frontend
- HTML/CSS

- GitHub for version control
---

## Project Summary

This project demonstrates how to build a domain-specific AI chatbot using LLMs and vector search. It processes a 637-page medical encyclopedia to create a structured knowledge base. Using Hugging Face MiniLM and Pinecone, the system performs semantic search to retrieve the most relevant information and pass it to OpenAI's GPT model for generating responses.

Key components include:

- Text chunking using LangChain’s RecursiveCharacterTextSplitter
- Generation of 5,000+ text embeddings
- Storage and retrieval using Pinecone
- Prompt engineering to guide model responses
- Real-time query handling through a Flask web app

---

## Key Insights

- Combining vector databases with LLMs enables precise information retrieval
- Careful chunking strategies improve LLM performance and preserve context
- Hosted LLMs simplify deployment while balancing cost and performance
- Modular, end-to-end design ensures maintainability and production readiness


