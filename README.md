# RAG System in Python

## Project Overview
This project is a simple **Retrieval-Augmented Generation (RAG)** system built in Python using **Hugging Face Transformers**. It combines the capabilities of a retriever model and a language generation model to answer user queries more effectively by grounding responses in relevant source documents.

The system works in two main steps:  
1. **Retrieval:** A retriever model searches a document collection or knowledge base to find relevant context for a given query.  
2. **Generation:** A language model generates an answer using both the user query and the retrieved context.  

## Features
- Uses Hugging Face Transformers for both retrieval and generation.
- Easily adaptable to custom datasets or knowledge bases.
- Provides more accurate and context-aware responses than a standard language model.
