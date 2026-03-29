# Assignment_1_Purplemerit
# Course Planner RAG pipeline

## Overview
This project implements a Retrieval-Augmented Generation (RAG) system for answering course-related queries using academic course catalogs.

## Features
- Document ingestion (HTML + PDF)
- Chunking and embeddings (SentenceTransformers)
- Vector database (ChromaDB)
- Retrieval + LLM (Groq)
- Advanced RAG with citations, summaries, and history

## Setup

```bash
pip install -r requirements.txt

Set API key:
export GROQ_API_KEY=your_key
