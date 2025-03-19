# PDF RAG Bot 

## Overview  
This is a **simple and basic RAG (Retrieval-Augmented Generation) bot** designed to process **PDF documents** and provide intelligent responses based on their content. The bot extracts text from PDFs, generates embeddings, retrieves relevant context, and uses an LLM to generate accurate answers.

## Features  
✅ **PDF Parsing** – Extracts text from uploaded PDF files.  
✅ **Embedding Generation** – Converts extracted text into vector embeddings for efficient retrieval.  
✅ **Contextual Retrieval** – Fetches the most relevant document sections for queries.  
✅ **LLM Integration** – Uses an AI model to generate responses based on retrieved data.  

## How It Works  
1. **Upload PDFs** – The bot processes the uploaded PDF and extracts text.  
2. **Embedding & Indexing** – The extracted content is converted into vector embeddings for efficient retrieval.  
3. **Query Processing** – Users enter queries, and the bot fetches relevant text chunks.  
4. **Response Generation** – The AI model formulates a response based on the retrieved content.  

## Tech Stack  
🔹 `LangChain` – For retrieval and LLM-based response generation.  
🔹 `PyPDF` – For extracting text from PDF documents.  
🔹 `ChromaDB` – For embedding storage and retrieval.  
🔹 `Gemini API` – For generating responses.  
  
