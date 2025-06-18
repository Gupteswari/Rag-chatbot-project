# 🧠 AI Health Assistant

An AI-powered assistant that reads, processes, and understands healthcare documents (PDFs) to provide intelligent search and recommendations using vector embeddings and Zilliz/Milvus.

---

## 📌 Objective

This project aims to create an AI-driven health assistant capable of:
- Reading and parsing medical PDF documents.
- Chunking and embedding the content using Google Gemini embeddings.
- Storing embeddings in a Zilliz/Milvus vector database.
- Performing intelligent semantic search on medical topics.

---

## 📂 Folder Structure

```
.
├── Data/                   # Folder containing medical PDF files
├── AI Health Assistant.ipynb          # Main Jupyter notebook
├── README.md                          # This file
```

---

## ⚙️ Features

- ✅ PDF reading and text extraction
- ✅ Text chunking using LangChain
- ✅ Embedding generation using Google Gemini API
- ✅ Vector storage with Zilliz/Milvus
- ✅ Query-based semantic search

---

## 🚀 How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/ai-health-assistant.git
cd ai-health-assistant
```

### 2. Install Requirements

```bash
pip install -r requirements.txt
```

### 3. Set Up API Key

Create a `.env` file or export your Google Gemini API key:

```bash
export GOOGLE_API_KEY='your_api_key'
```

### 4. Add PDFs

Place your healthcare-related PDFs into the `healthcare_pdfs/` folder.

### 5. Run the Notebook

Launch the Jupyter notebook and run all cells:

```bash
jupyter notebook
```

---

## 🔍 Example Query

```python
query = "What are symptoms of diabetes?"
```

Returns the most relevant document chunks using vector search from Milvus.

---

## 🧠 Technologies Used

- Python 🐍
- LangChain 🦜
- Google Generative AI (Gemini)
- Milvus / Zilliz Vector DB
- PyPDF2 for PDF parsing


