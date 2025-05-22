# ChatGroq with LLaMA3 Demo

This project is a Streamlit-based web application that allows users to interact with documents using LLaMA3 via ChatGroq. The app ingests PDF documents, creates vector embeddings using FAISS, and retrieves document-based answers through a conversational interface.

# 🔧 Features
Upload and embed a directory of PDFs using PyPDFDirectoryLoader

Vectorize documents with FAISS and OllamaEmbeddings

Query documents using natural language

Retrieve accurate context-based answers using LLaMA3 (Groq API)

View similar documents retrieved from vector search

# 🛠️ Tech Stack
Streamlit – UI Framework

LangChain – Document loading, chaining, and vector search

FAISS – Vector similarity search

Groq – LLM API backend (LLaMA3)

OllamaEmbeddings – Text embedding model

dotenv – Environment variable management

# ✨ How It Works
Document Embedding:

Click the "Documents Embedding" button to load, chunk, and vectorize the PDF files.

Ask a Question:

Enter a question related to the embedded documents in the input box.

Receive Answer:

The LLM processes your question using the most relevant documents and responds accurately.

Document Context:

Expand the “Document Similarity Search” section to see which document snippets were retrieved to answer the question.
