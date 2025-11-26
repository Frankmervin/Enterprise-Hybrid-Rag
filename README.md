# Enterprise-Hybrid-RAG
Every day, the system downloads new arXiv PDFs, extracts knowledge, stores it smartly, and makes it searchable for an LLM to answer your questions

##  Enterprise Hybrid RAG + LLMOps 

### This project demonstrates how a real enterprise GenAI system is designed and deployed using AWS, AI search engines, modern LLMs, and continuous learning workflows.

####    The goal is to explain the entire architecture in a simple, minimalist, and practical way, without overwhelming implementation details.

This repository is built as a blueprint that shows not just what to build, but why each component matters and how the system evolves over time.

🧠 Why This Blueprint Exists

Modern companies don’t want “just a chatbot.”
They want:

*   Automated data pipelines

*   Hybrid search systems

*   High-quality retrieval-augmented answers

*   A platform that can learn from users

*   Proper LLMOps for reliability, monitoring, rollbacks, and versioning

*   Cloud-ready deployment

####    This project blueprint teaches exactly how real enterprise GenAI products are built, but explained in the simplest possible way.

It focuses on architecture clarity, not complex code.

<b>🌟 What This Platform Does (Minimal Explanation)</b>

This system:

<i>Automatically downloads arXiv PDFs daily

Converts PDF → structured knowledge (titles, abstracts, sections)

Stores metadata in PostgreSQL (RDS)

Splits content into semantic chunks

Embeds and indexes chunks in AWS OpenSearch
(BM25 + Vector Search = Hybrid Search)

Uses LlamaIndex to orchestrate retrieval

Uses an LLM (local or API) to generate grounded answers

Tracks everything using Langfuse

Evaluates quality using RAGAS + ranking metrics

Lets users give feedback to improve the system

Builds datasets for fine-tuning and future training

Supports full LLMOps: versioning, monitoring, A/B testing, rollback

Provides a FastAPI backend + Streamlit frontend</i>

####    All explained in minimalist language, the way an engineering manager expects.