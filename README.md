# Mental Health Support Chatbot

## Overview
The **Mental Health Support Chatbot** is an AI-powered assistant designed to provide guidance and support for mental health-related concerns. Built using **LangChain** and **Llama-3.3-70B-Versatile**, the chatbot leverages a **Retrieval-Augmented Generation (RAG) pipeline** to provide accurate and relevant responses based on a mental health document corpus.

## Features
- Utilizes **Llama-3.3-70B-Versatile** as the foundational large language model (LLM).
- Implements **RAG pipeline** using **LangChain** for enhanced retrieval and response generation.
- Processes mental health documents with **text splitting** for optimized chunking.
- Embeds text using **Hugging Face word embeddings**.
- Stores embeddings in a **ChromaDB vector database**.
- Implements a **QA Chain** for efficient querying and response generation.
- Provides a user-friendly chat interface built with **Gradio**.

## Tech Stack
- **LLM**: Llama-3.3-70B-Versatile
- **Framework**: LangChain
- **Embeddings**: Hugging Face Word Embeddings
- **Vector Database**: ChromaDB
- **Chat Interface**: Gradio

## Project Workflow
1. **Load Mental Health Documents**: The dataset containing mental health-related content is ingested.
2. **Apply Text Splitter**: The documents are split into meaningful chunks to optimize retrieval.
3. **Generate Embeddings**: The chunks are converted into numerical representations using **Hugging Face embeddings**.
4. **Store in ChromaDB**: The embeddings are stored in a **ChromaDB** vector database for efficient retrieval.
5. **Setup QA Chain**: A **Question-Answering (QA) Chain** is configured in **LangChain** to enable the chatbot to fetch relevant responses.
6. **Build Gradio Chat Interface**: A user-friendly chat interface is created using **Gradio** for seamless interactions.

## Usage
1. Open the Gradio interface in your browser.
2. Input your query regarding mental health.
3. The chatbot retrieves relevant information and provides a response.
