# Content_Engine
This project focuses on creating a sophisticated Content Engine Bot designed to analyze and compare multiple PDF documents, specifically Form 10-K filings from Alphabet Inc., Tesla, Inc., and Uber Technologies, Inc. The system leverages Retrieval Augmented Generation (RAG) techniques to retrieve, assess, and generate insights from the documents.
# Content Engine Bot

## Overview
Content Engine Bot is a Streamlit-based application designed to analyze and compare multiple PDF documents, providing insights based on user queries. The application uses a SentenceTransformer model to embed document content and a GPT-2 model to generate insights. The interface is designed to resemble a chatbot, making it user-friendly and interactive.

## Features
- **Chatbot-like Interface**: Engaging and user-friendly interface for querying and receiving insights.
- **PDF Parsing and Embedding**: Parses text from PDF documents and embeds the content using a SentenceTransformer model.
- **Insight Generation**: Generates insights based on user queries using a GPT-2 model.
- **Dedicated to Uber, Tesla, and Alphabet Companies**: Focused on analyzing documents related to these companies.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/content-engine-bot.git
   cd content-engine-bot
