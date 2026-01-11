# NVIDIA-NIM-App
RAG Application Using NVIDIA NIM and Langchain

A Retrieval-Augmented Generation (RAG) application built with Streamlit, LangChain, NVIDIA AI Endpoints, and FAISS that allows users to ask questions about a PDF document and get accurate, context-aware answers.
//Features
-Load and process PDF documents
-Chunk text using recursive splitting
-Generate embeddings using NVIDIAEmbeddings
-Store and search vectors with FAISS
-Answer questions using ChatNVIDIA (LLaMA instruct model)
-View retrieved document chunks for transparency
-Interactive UI built with Streamlit

//Tech Stack
-Python
-Streamlit
-LangChain
-NVIDIA AI Endpoints (NIM)
-FAISS (CPU)
-PyPDFLoader
-dotenv
