# 📚 Semantic Book Recommender App

A semantic book recommendation system that uses **transformer-based embeddings**, **zero-shot classification**, and **vector search** to recommend books based on user input. Built with **LangChain**, **Transformers**, and a user-friendly interface powered by **Gradio**.

---

## ✨ Features

- 🔍 **Semantic Search**: Find books based on meaning, not keywords.
- 🎯 **Zero-Shot Classification**: Categorize and filter books without labeled training data.
- 💬 **Gradio Interface**: Simple and interactive frontend to explore recommendations.
- ⚡ **Fast Vector Search**: Using ChromaDB to store and retrieve book embeddings.

---

## 🚀 Technologies Used

| Tech             | Purpose                           |
|------------------|------------------------------------|
| LangChain        | Text processing and document management |
| Hugging Face Transformers | Embeddings and classification |
| ChromaDB         | Vector database backend            |
| SentenceTransformers | Pre-trained models like `bge-small-en-v1.5` |
| Gradio           | Web-based UI for interaction       |
| PyTorch          | Backend for model execution        |

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/book-recommender-llm.git
cd book-recommender-llm
```

### 2. Set up a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

