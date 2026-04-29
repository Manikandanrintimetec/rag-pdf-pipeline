# 🚀 RAG PDF Pipeline (Notebook Version)

This repository demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline using a Jupyter Notebook.

It processes a PDF document, converts it into embeddings, and retrieves relevant information to answer user queries using an LLM.

---

## 📂 Project Structure

```bash
rag-pdf-pipeline/
│
├── chain/
│   ├── retriever.ipynb
│   ├── attention.pdf
```

---

## 🧠 Pipeline Flow

```text
PDF → Load → Split → Embeddings → FAISS → Retriever → LLM → Answer
```

---

## ⚙️ Setup

### 1️⃣ Install dependencies

```bash
pip install langchain langchain-core langchain-community \
langchain-openai langchain-text-splitters \
sentence-transformers faiss-cpu pypdf python-dotenv jupyter
```

---

### 2️⃣ Add API Key

Create a `.env` file in the root directory:

```text
OPENROUTER_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

```bash
jupyter notebook chain/retriever.ipynb
```

Run all cells step by step.

---

## 💡 Example Query

```
What is Scaled Dot-Product Attention?
```

---

## 📌 Notes

* Ensure `attention.pdf` is in the same folder as the notebook
* Do not commit `.env` file
* Best compatible with Python 3.10 / 3.11

---

## 🚀 Future Improvements

* Convert notebook into Python script
* Add FastAPI backend
* Build Streamlit UI
* Support multiple PDFs

---

## 👨‍💻 Author

Manikandan R

---

## ⭐ Support

If you like this project:

👉 Star ⭐ the repo
👉 Share 🚀
