# Content Engine Bot

## Project Description

This project focuses on creating a sophisticated Content Engine Bot designed to analyze and compare multiple PDF documents, specifically Form 10-K filings from Alphabet Inc., Tesla, Inc., and Uber Technologies, Inc. The system leverages Retrieval Augmented Generation (RAG) techniques to retrieve, assess, and generate insights from the documents.

## Setup

### Backend Framework

- **LlamaIndex**: A flexible framework for creating custom retrieval systems.
- **LangChain**: A toolkit for building LLM applications with a focus on retrieval-augmented generation.

### Frontend Framework

- **Streamlit**: An open-source app framework for Machine Learning and Data Science projects, facilitating the creation of interactive web applications.

### Vector Store

Options include ChromaDB, Pinecone, Faiss, Milvus, Weaviate, etc.

### Embedding Model

A local embedding model is used for generating vectors from the PDF content.

### Local Language Model (LLM)

A local instance of a Large Language Model is integrated for processing and generating insights, ensuring no exposure to external APIs.

## Initialization

Three PDF documents containing the Form 10-K filings of Alphabet, Tesla, and Uber are provided. The task is to retrieve content from these PDFs, compare them, and answer queries highlighting the differences and insights across all documents. The system features a chatbot interface for user interaction, facilitating queries and obtaining insights about the documents.

## Development Steps

1. **Parse Documents**: Extract text and structure from PDFs.
2. **Generate Vectors**: Use a local embedding model to create embeddings for document content.
3. **Store in Vector Store**: Utilize local persisting methods in the chosen vector store.
4. **Configure Query Engine**: Set up retrieval tasks based on document embeddings.
5. **Integrate LLM**: Run a local instance of a Large Language Model for contextual insights.
6. **Develop Chatbot Interface**: Use Streamlit to facilitate user interaction and display comparative insights.

## Features

- **Interactive Chatbot Interface**: Engages users with a friendly and intuitive chatbot interface.
- **Comprehensive Analysis**: Provides insights into risk factors, revenue, and business differences among the companies.
- **Secure and Local Processing**: Ensures all models and data processing are handled locally, maintaining data privacy and security.


