# QA Bot Web App with LangChain, Watsonx, Chroma, and Gradio

This project is a Retrieval-Augmented Generation (RAG) question-answering bot that allows users to upload a PDF and ask questions about its contents.

## Features
- PDF document loading with LangChain
- Text chunking with RecursiveCharacterTextSplitter
- Embeddings using IBM watsonx
- Vector storage with Chroma
- Retrieval-based question answering
- Gradio web interface

## Tech Stack
- Python
- LangChain
- IBM watsonx.ai
- ChromaDB
- Gradio

## Project Structure
- `qabot.py` - main application
- `requirements.txt` - dependencies
- `screenshots/` - course submission screenshots

## Installation

```bash
pip install virtualenv
virtualenv my_env
source my_env/bin/activate
pip install -r requirements.txt
