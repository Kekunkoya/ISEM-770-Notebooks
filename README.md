##Retrieval-Augmented Generation (RAG) Techniques – OpenAI & Gemini

---
## Overview
This folder contains Jupyter notebooks demonstrating Retrieval-Augmented Generation (RAG) techniques using both OpenAI and Google Gemini models.
The goal is to understand, compare, and evaluate how each model handles RAG pipelines for information retrieval and question answering.

---
## Contents
RAG_OpenAI.ipynb – End-to-end RAG pipeline using OpenAI embeddings and chat models.
RAG_Gemini.ipynb – RAG implementation with Google Gemini embeddings and text generation.
RAG_Comparison.ipynb – Side-by-side evaluation of OpenAI vs Gemini responses with quality metrics (BERTScore, cosine similarity).
data/ – Example PDF and JSON datasets used for retrieval.
utils/ – Helper functions for text chunking, embedding creation, retrieval, and evaluation.
---
##How to Run
Install dependencies:
pip install -r requirements.txt
Set up API keys as environment variables:
export OPENAI_API_KEY="your_openai_key_here"
export GOOGLE_API_KEY="your_google_key_here"
Open any notebook in Jupyter or Google Colab and run the cells sequentially.


## Key Features
PDF ingestion & chunking for efficient retrieval
Separate vector stores for OpenAI and Gemini embeddings
Multiple evaluation metrics to assess answer quality


##Purpose
These notebooks are designed for:
Learning how to set up a RAG pipeline
Understanding differences between OpenAI and Gemini in retrieval tasks
Evaluating model accuracy, relevance, and consistency
