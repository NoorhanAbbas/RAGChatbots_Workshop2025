# RAG Chatbots Workshop 2025

Welcome to the **RAG Chatbots Workshop 2025**, a hands-on learning experience designed to help educators build and deploy Retrieval-Augmented Generation (RAG)-powered chatbots with ease.

---

## 🎯 Objective

The goal of this task is to develop a **user-friendly interface application** that enables educators to generate a fully functional chatbot using their own PDF teaching materials.

This chatbot application:
- Uses RAG to generate accurate, source-grounded responses
- Accepts multiple PDF files as the knowledge base
- Allows selection of response complexity levels
- Automatically generates all required deployment files

---

## 🛠️ Auto-Generated Files

Based on the educator’s input, the system produces the following:

- `app.py`: Main chatbot application using Streamlit  
- `requirements.txt`: Python dependencies for deployment  
- **Uploaded PDF files**: Used as the knowledge base  
- `README.md` and step-by-step **setup manual**  

---

## 📘 Educator Manual Overview

The included guide walks educators through:

### 🔐 Hugging Face Setup
- How to create a Hugging Face account
- How to generate and store API tokens in the **Secrets** tab of Hugging Face Spaces
- How to request access to gated models

### ⚙️ Hardware Configuration
- Choosing the right hardware (CPU vs GPU)
- Understanding T4 and other accelerator options
- Optimizing Hugging Face Space settings for your chatbot

### 🚀 Deploying and Using the Chatbot
- How to upload files and run the chatbot
- How to test and interact with it
- How to interpret answers with **source references**

---

## 💡 Features

- Context awareness and basic memory  
- Answers based only on uploaded PDF content  
- Handles greetings and conversation flow  
- Offers response **complexity levels**  
- Displays **retrieved source** for transparency  
- Asks back-questions to enrich engagement  

---

## 🧰 Tools and Technologies

- [Streamlit](https://streamlit.io/)
- [Hugging Face Spaces](https://huggingface.co/spaces)
- [Hugging Face Models (quantized)](https://huggingface.co/models)
- [LangChain](https://www.langchain.com/)
- [ChromaDB](https://www.trychroma.com/) or [FAISS](https://github.com/facebookresearch/faiss)
- Sentence Transformers / Embedding Models

---

## 📁 Repository Structure (Example)

```bash
📦 RAGChatbots_Workshop2025/
│
├── app.py                     # Streamlit chatbot script
├── requirements.txt           # Project dependencies
├── /notebooks                 # Jupyter Notebooks for demos
├── /data                      # Example PDFs or text files
├── README.md                  # This file
└── index.md                   # GitHub Pages homepage
