# 📚 Full RAG Application

## Overview

This is a **Retrieval-Augmented Generation (RAG) Application** that enables users to upload various types of files, store them in a structured database, and query them efficiently. The system allows users to manage multiple projects, each with its own set of files, and offers customizable options like **chunk size, overlap settings**, and more.

The application is built using **FastAPI**, **PostgreSQL**, and **Qdrant** for vector storage.

## 🔥 Features

- 🔄 **Multi-Project Management** – Create and organize multiple projects, each with its own set of files and configurations.
- 📂 **File Upload & Processing** – Supports a wide range of formats, including **PDFs, DOCX, TXT**, and more.
- 🏗️ **Intelligent Chunking & Overlapping** – Customize chunk size and overlap settings to optimize text segmentation and retrieval.
- 🏛️ **Hybrid Database Architecture** – Store structured metadata in **PostgreSQL** and high-dimensional embeddings in **Qdrant** for blazing-fast semantic search.
- 🤖 **AI-Powered Querying** – Retrieve relevant document snippets using **state-of-the-art embeddings** powered by OpenAI and Cohere.
- 🚀 **Scalable & High-Performance API** – Built with **FastAPI**, ensuring rapid and asynchronous interactions for real-time document retrieval.
- 🛠️ **Seamless Integrations** – Designed to work with multiple LLMs and retrieval frameworks such as **LangChain**.

## 🛠️ Technologies Used

- **FastAPI** – High-performance API framework for rapid development
- **PostgreSQL** – Relational database for structured data storage
- **Qdrant** – Vector database for high-speed embedding retrieval
- **LangChain** – Intelligent orchestration of document processing and retrieval
- **PyMuPDF** – PDF parsing and text extraction
- **Motor** – Async MongoDB driver (for optional caching & additional storage)
- **OpenAI / Cohere** – Embedding models for powerful semantic search
- **SQLAlchemy** – ORM for database interactions
- **Asyncpg** – Async PostgreSQL driver for scalability
- **Alembic** – Database migration and version control tool
- **Psycopg2** – PostgreSQL adapter for Python applications



