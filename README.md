# GenAI – Document Question Answering System

A **Generative AI-powered Document Q&A application** built using Python, Streamlit, and LangChain. It allows users to upload documents and ask questions based on their content using a Retrieval-Augmented Generation (RAG) pipeline.

## Features
- Upload PDF, DOCX, and TXT files.
- Extract and split document content into chunks.
- Generate embeddings using OpenAI.
- Store and retrieve information using ChromaDB.
- Ask questions and get AI-generated answers.
- View previous questions and answers.
- Calculate document embedding costs.

## Technologies Used
- Python
- Streamlit
- LangChain
- OpenAI API
- ChromaDB
- Tiktoken

## RAG Workflow
1. Document Upload
2. Text Extraction
3. Text Chunking
4. Embedding Generation
5. Vector Storage
6. Similarity Search
7. LLM Response Generation

## Installation

```bash
pip install -r requirements.txt
```

## Setup

Create a `.env` file and add your OpenAI API key:

```env
OPENAI_API_KEY=your_api_key
```

## Run the Application

```bash
streamlit run chat_with_documents.py
```

## Author
**ARNAB PANDIT**
