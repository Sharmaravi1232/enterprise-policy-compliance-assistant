# enterprise-policy-compliance-assistant
Enterprise AI assistant using RAG, web search, YouTube Q&amp;A, and intelligent document retrieval with LangChain and GPT-4o-mini.
# Enterprise Policy & Compliance Assistant

AI-powered enterprise assistant designed for intelligent compliance support, document retrieval, and real-time regulatory assistance.

## Overview

This project implements a production-style multi-agent AI system capable of:

* Enterprise Retrieval-Augmented Generation (RAG)
* Dynamic document ingestion
* Real-time web search intelligence
* YouTube transcript question answering
* Intelligent query routing
* Telemetry and observability logging

The system was developed as part of an AI Engineer technical assessment focused on enterprise AI architecture and orchestration.

---

## Core Features

### Enterprise RAG Pipeline

* PDF, DOCX, and TXT document support
* Semantic retrieval using FAISS
* Context-grounded answer generation

### Web Search Agent

* Real-time regulatory and compliance search
* Dynamic external knowledge retrieval

### YouTube Q&A

* Transcript extraction and analysis
* Video-based question answering

### Intelligent Query Router

* Dynamic routing between:

  * RAG
  * Web Search
  * YouTube Q&A
  * General Chat

### Telemetry & Observability

* Response time tracking
* Tool usage logging
* Error monitoring
* Execution visibility

---

## Technology Stack

* OpenAI GPT-4o-mini
* LangChain
* FAISS
* HuggingFace Embeddings
* Gradio
* Hugging Face Spaces

---

## Project Architecture

User Query
→ Intelligent Query Router
→ RAG / Web Search / YouTube Q&A
→ GPT-4o-mini Reasoning
→ Final Response
→ Telemetry Logging

---

## Deployment

The application is deployed using:

* Gradio
* Hugging Face Spaces

---

## Installation

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

---

## Environment Variable

Create the following secret/environment variable:

```bash
OPENAI_API_KEY=your_api_key
```

---

## Author

Ravi Shankar Sharma
