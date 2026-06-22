RAG-Based Document Question Answering System

Built an AI-powered Document Question Answering System using n8n, OpenAI, Pinecone, Google Drive, and Railway. This project implements a Retrieval-Augmented Generation (RAG) pipeline that automatically processes documents, generates embeddings, stores them in a vector database, and answers user queries using relevant document context.

Workflow Overview

1. Google Drive Integration – Detects and retrieves uploaded or updated documents.
2. Document Processing – Extracts and splits document content into manageable text chunks.
3. OpenAI Embeddings – Converts text chunks into vector embeddings for semantic understanding.
4. Pinecone Vector Store – Stores embeddings for efficient similarity search and retrieval.
5. AI Agent – Retrieves relevant context from Pinecone and generates accurate responses using OpenAI.
6. Chat Interface – Enables users to ask natural language questions about uploaded documents.

Features

* Automated workflow orchestration using n8n
* Document ingestion and processing from Google Drive
* Semantic search using vector embeddings
* Retrieval-Augmented Generation (RAG) architecture
* Context-aware question answering
* Real-time document updates and synchronization
* Cloud deployment on Railway

Tech Stack

* n8n (Workflow Automation & AI Orchestration)
* OpenAI (Embeddings & Language Model)
* Pinecone (Vector Database)
* Google Drive API
* Railway (Cloud Deployment)

Outcome

The system allows users to upload any document and interact with it through a chat interface. By combining semantic search with large language models, the chatbot can provide accurate, context-aware answers directly from the document content.

Through this project, I gained hands-on experience with AI workflow automation, vector databases, Retrieval-Augmented Generation (RAG), OpenAI integration, and cloud deployment.
