# RAG-Powered VisionChatbot: Offline Vision and Decentralized Data on CPU

## Overview

This project demonstrates a CPU-compatible chatbot built using open-source LLMs and RAG architecture. It's designed for efficient inference on CPU-based systems, enabling broader access to language model capabilities.

Key Features:

LLM-powered chatbot: Leverages LLMs for engaging and informative conversations.
RAG architecture: Employs the Retrieval-Augmented Generation approach for enhanced response quality.
CPU-friendly: Optimized for smooth operation on CPU, expanding accessibility.
Memory chain: Retains context for more coherent and natural dialogues.
Image search integration (planned): Will incorporate image search functionality using transfer learning CV models for a multimedia experience.
Decentralized database (planned): Aims to utilize blockchain technology for a secure and distributed database.
## Getting Started

Download the model:

Obtain the llama-2-7b-chat.ggmlv3.q8_0.bin model from Hugging Face: https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin
Place it in the project's main directory.
Create a virtual environment:

Isolate project dependencies using a virtual environment (e.g., venv or conda).
Install dependencies:

Run pip install -r requirements.txt to install required libraries.
## Usage

(*OPTIONAL*)Inside Data place your own pdf and delete the already present files inside vectorstore/db_faiss , then run python ingest.py

Execute the main script (e.g., chainlit run model.py -w) to start the chatbot.
