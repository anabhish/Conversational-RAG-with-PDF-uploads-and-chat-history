# Conversational RAG with PDF Uploads and Chat History

## Overview

This project is a Retrieval-Augmented Generation (RAG) application that enables users to upload PDF documents and interact with them through a conversational interface. It combines semantic search with a large language model to provide context-aware answers while preserving chat history for follow-up questions.

## Features

* Upload and process PDF documents
* Conversational question answering with chat history
* Semantic retrieval using vector embeddings
* Fast inference with Groq LLMs
* Interactive web interface built with Streamlit

## Tech Stack

* Python
* Streamlit
* LangChain
* ChromaDB
* Hugging Face Embeddings (`BAAI/bge-small-en-v1.5`)
* Groq API
* PyPDF

## Installation

```bash
git clone https://github.com/<your-username>/Conversational-RAG-with-PDF-uploads-and-chat-history.git

cd Conversational-RAG-with-PDF-uploads-and-chat-history

pip install -r requirements.txt

streamlit run ConversationalQAchatboat/ConversationalQnAchatboat_using_PDF.py
```

## Configuration

For local development, create a `.env` file:

```text
GROQ_API_KEY=your_groq_api_key
```

For Streamlit Cloud deployment, configure the API key using **Secrets** instead of a `.env` file.

## Project Structure

```text
Conversational-RAG-with-PDF-uploads-and-chat-history/
│
├── ConversationalQAchatboat/
│   └── ConversationalQnAchatboat_using_PDF.py
├── requirements.txt
├── README.md
└── .gitignore
```

## Future Improvements

* Multi-document retrieval
* Source citations
* Persistent vector storage
* Streaming responses
* Docker support

## License

This project is intended for educational and portfolio purposes.
