# 🚀 Build a RAG API with FastAPI

This project demonstrates how to build a **Retrieval-Augmented Generation (RAG) API** using **FastAPI, ChromaDB, and Ollama**. It allows you to store personal information in a knowledge base, retrieve relevant data, and generate AI-powered answers.

---

## 🛠️ Tech Stack

- Python  
- FastAPI  
- Uvicorn  
- ChromaDB  
- Ollama  

---

## ⚙️ Step-by-Step Guide

### 01. Install Ollama
Download and install Ollama from the official website: https://ollama.com

### 02. Set Up Python Project
Create a new project folder for your RAG API.

### 03. Check Python Version
Ensure Python 3.8 or higher is installed on your machine.

### 04. Create a Virtual Environment
Set up a virtual environment to manage your project dependencies.

### 05. Install Required Packages
Install all necessary Python packages including FastAPI, Uvicorn, ChromaDB, and Ollama.

### 06. Pull the Embedding Model
Download the embedding model `nomic-embed-text` for use with your knowledge base.

### 07. Create `profile.txt`
Create a file named `profile.txt` to store personal information or any data you want the RAG system to use.

### 08. Add Personal Information
Write your personal details or relevant data into `profile.txt`.

### 09. Build Knowledge Base Script
Create a Python script that reads the `profile.txt` file and adds its content to ChromaDB as embeddings.

### 10. Run the Knowledge Base Script
Execute the script to generate your knowledge base.

### 11. Create RAG API
Develop a FastAPI application that queries the knowledge base and generates answers using an LLM.

### 12. Test Using Swagger UI
Run the FastAPI server, open the Swagger UI in your browser, and test the `/ask` endpoint by asking questions like "What is my name?"

---

## ✅ How It Works

1. **Embedding** → Convert text into numerical vectors  
2. **Storage** → Save vectors in ChromaDB  
3. **Retrieval** → Find the most relevant information  
4. **Generation** → LLM generates answers based on retrieved context  

---

## 📂 Project Structure

- `profile.txt` → Personal or knowledge base data  
- `build_knowledge_base.py` → Script to create the knowledge base  
- `main.py` → FastAPI application for the RAG API  
- `venv/` → Python virtual environment  

---

## 📄 License
Santhush Ekanayake 2026 @NextWork Projects
