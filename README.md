# Enterprise RAG Knowledge Assistant & Evaluation Dashboard

This is a professional-grade Retrieval-Augmented Generation (RAG) system designed to act as an expert knowledge worker for corporate insurance data. This project implements a complete LLM-Ops pipeline: from automated document ingestion and vectorization to a sophisticated evaluation dashboard that measures retrieval precision and answer quality using LLM-as-a-judge.

# Key Features

**Advanced RAG Pipeline**: Utilizes text-embedding-3-large for high-dimensional semantic search and gpt-4.1-nano for context-aware response generation.

**Intelligent Ingestion**: Automated processing of markdown files with recursive character splitting and metadata tagging.

## Dual-Interface Design

**Expert Chatbot**: A polished Gradio UI for real-time conversation with full visibility into retrieved source context.

**Evaluation Dashboard**: A specialized UI for benchmarking system performance across different categories.

## Rigorous Evaluation Suite

**Retrieval Metrics**: Calculates MRR (Mean Reciprocal Rank), nDCG (Normalized Discounted Cumulative Gain), and Keyword Coverage.

**Answer Metrics**: Accuracy, Completeness, and Relevance scores (1-5 scale) judged by a secondary LLM instance.

# System Previews

1. **Expert Knowledge Assistant**

[INSERT YOUR CHATBOT SCREENSHOT HERE] 

The Chatbot interface features a dual-pane view: the conversational UI on the left and the raw retrieved context on the right for full transparency.

2. **RAG Evaluation Dashboard**

[INSERT YOUR EVALUATOR SCREENSHOT HERE] 

The Dashboard visualizes retrieval performance across categories (direct fact, spanning, temporal) and provides color-coded health metrics for system accuracy.

# Tech Stack

**Orchestration**: LangChain.

**Vector Store**: ChromaDB.

**Embeddings**: OpenAI text-embedding-3-large.

**Models**: gpt-4.1-nano (via OpenAI & LiteLLM).

**UI Framework**: Gradio.

**Package Management**: uv.
