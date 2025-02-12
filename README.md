# 📄 Multi-Source Querying App (RAG-Based) 📝🔍

This Streamlit-powered **Multi-Source Querying App** allows users to upload documents (PDF, DOCX, PPTX, URLs, CSV, Excel) and extract their content for querying using **Retrieval-Augmented Generation (RAG)** and **SQL-based querying**. The app leverages **FAISS** for vector-based document retrieval and uses an LLM-powered agent for SQL queries.

---

## 🚀 Features
- 📄 **Document Processing**: Extract text from **PDF, DOCX, PPTX, and Web URLs**.
- 🔍 **RAG-Based Question Answering**: Uses FAISS for **vector storage** and retrieval.
- 🗂 **SQL Querying**: Upload and query **CSV/Excel** data using **SQL**.
- ⚡ **Fast & Efficient**: Uses **Google Generative AI** for embeddings & **Groq LLM** for answering queries.

---

## 📌 Installation

### 1️⃣ Access the Repository
```sh
git clone https://github.com/Ashish-Ram0906/RAG.git
cd your-repo
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
pip install -r requirements.txt
streamlit run app.py
