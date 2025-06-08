Current project Loan AI - RAG Implementation copyright AshUprety 1system LLC 
 
## Overview
This project implements a Retrieval-Augmented Generation (RAG) system for loan-related queries using:
- OpenAI GPT-4 for generation
- Pinecone vector database for document storage
- Streamlit for the user interface
- LangChain for orchestration
 
## Features
- **Document Processing**: Load and process various loan-related documents (PDF, DOCX, Markdown)
- **Semantic Search**: Find relevant loan information using vector embeddings
- **Context-Aware Responses**: Generate accurate responses using GPT-4 with retrieved context
- **User Interface**: Interactive web interface for querying loan information
 
## Installation
 
1. Clone the repository:
   ```bash
   git clone 
   cd loan-ai
   ```
 
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
 
3. Set up environment variables:
   Create a `.env` file with:
   ```
   PINECONE_API_KEY=your_pinecone_key
   PINECONE_ENVIRONMENT=your_environment
   OPENAI_API_KEY=your_openai_key
   ```
 
## Usage
 
1. Start the Streamlit app:
   ```bash
   streamlit run app.py
   ```
 
2. Access the web interface at `http://localhost:8501`
 
