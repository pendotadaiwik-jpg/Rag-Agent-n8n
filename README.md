# RAG Agent using n8n, Google Gemini, and Supabase

## Overview
This project implements a Retrieval-Augmented Generation (RAG) workflow using n8n, Google Gemini, and Supabase. It allows users to ask questions and receive AI-generated answers grounded in information retrieved from stored documents.

## Workflow
1. **Document Ingestion:** Google Drive monitors a specified folder for documents.
2. **File Download:** Downloads documents for processing.
3. **Embeddings Generation:** Google Gemini generates embeddings for document content.
4. **Vector Storage:** Stores document embeddings in a Supabase vector store.
5. **User Query:** A chat trigger receives the user's question.
6. **Context Retrieval:** The agent retrieves relevant information from the vector store.
7. **AI Response:** Google Gemini generates an answer using the retrieved context.

## Technologies Used
- **n8n** — workflow automation and AI orchestration
- **Google Drive** — document storage
- **Google Gemini** — language model and embeddings
- **Supabase** — vector storage and semantic search

## Key Features
- Document ingestion workflow
- Embedding-based document retrieval
- Retrieval-Augmented Generation (RAG)
- Context-grounded question answering
- Integration of AI models and vector storage

## Project Status
Portfolio project. Google Drive and Supabase credentials, resource IDs, and required integrations must be configured before running the workflow.

## Security Note
The workflow JSON shared in this repository is a sanitized export. Configure your own credentials and resource IDs before importing and running it. Never upload API keys, passwords, or private documents.
