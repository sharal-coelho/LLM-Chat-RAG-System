# LLM Chat + RAG System

A lightweight Large Language Model project using Hugging Face Transformers.
Supports chat-style inference and Retrieval-Augmented Generation (RAG).

## Features
- Transformer-based LLM
- Local or cloud inference
- Optional RAG using FAISS



# What is RAG (Retrieval-Augmented Generation)?
Retrieval-Augmented Generation (RAG) is a technique that combines information retrieval with large language models (LLMs) to generate more accurate, up-to-date, and grounded answers.
Instead of relying only on what the LLM learned during training, RAG retrieves relevant external documents and uses them as context before generating a response.

LLMs have limitations:
* Hallucinate facts
*  Knowledge is static (cutoff date)
*  Cannot access private or domain-specific data

RAG solves this by:

*Injecting external knowledge
*Reducing hallucinations
*Enabling enterprise/private data QA

✅ Enabling enterprise/private data QA
