# RAG Chatbot using LLM

## Overview

Built an AI-powered Retrieval-Augmented Generation (RAG) chatbot that answers user questions based on uploaded or indexed documents instead of relying only on pretrained knowledge.

## Features

* Accepts user questions in natural language
* Retrieves relevant document chunks
* Uses embeddings for semantic search
* Sends retrieved context to LLM
* Generates context-aware responses
* Reduces hallucination and improves accuracy

## Workflow

User Question
→ Convert to Embeddings
→ Vector Search
→ Retrieve Relevant Context
→ Send Context to LLM
→ Generate Answer

## Technologies Used

* Python
* LangChain
* LLM API
* Vector Database
* Embeddings
* FastAPI (if used)

## Example

Input:
What is Retrieval-Augmented Generation?

Retrieved Context:
Relevant document sections

Output:
Generated answer based on retrieved content.
