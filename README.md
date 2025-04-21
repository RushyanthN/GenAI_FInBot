Financial Assistant with Google GenAI and 10-K Filings
This project demonstrates how to build an AI-powered financial assistant that can analyze 10-K filings and answer questions about companies' financial information using Google's Generative AI.

📌 Overview
This application extracts, processes, and analyzes financial data from SEC 10-K filings to provide intelligent insights and answers to financial queries through a straightforward yet powerful approach:

Extract text from PDF documents
Convert to structured JSON using Google Gemini with few-shot prompting
Create embeddings with Sentence Transformers
Store in ChromaDB vector database
Implement RAG (Retrieval-Augmented Generation) pipeline
Generate controlled, structured responses through few-shot prompting

🚀 Features

Text Extraction: Direct extraction from 10-K financial filings in PDF format
Structured Data Conversion: Transform unstructured text to JSON using few-shot prompting
Semantic Search: Utilize Sentence Transformers embeddings for accurate information retrieval
RAG Pipeline: Implementation of Retrieval-Augmented Generation for improved accuracy
Controlled Output Generation: Produce consistent, structured responses through LLM training

🛠️ Technical Architecture

Data Extraction & Processing:

Direct PDF text extraction
Text preprocessing and cleaning
Conversion to structured JSON via Gemini models with few-shot prompting


Embedding & Storage:

Sentence Transformers for generating text embeddings
ChromaDB for vector storage and similarity search


RAG Implementation:

- Context retrieval from vector database
- Query enhancement and context integration
- Response generation using few-shot prompting techniques



📋 Prerequisites

Python 3.9+
Google API key for Gemini models
Libraries: sentence-transformers, chromadb, PyPDF2, etc.

# **5. Future Work**

The broader vision for this project includes:

-  Evaluating LLM responses against gold-standard queries and ground truth answers to ensure factuality and reliability.(Immediate)

- Extracting a wide range of financial, strategic, and operational data from filings.

- Supporting multiple companies and parsing both 10-K and 10-Q reports.

- Building pipelines using agents to autonomously extract, embed, and update data.

- Developing a web app with an interactive dashboard for querying and exploring filings.

- Benchmarking various LLMs (e.g., GPT-4, Gemini, Claude) on financial document understanding tasks
